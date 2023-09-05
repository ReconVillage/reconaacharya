# What is ReconAacharya Contest?
Introducing “Recon Aacharya Contest” – a mind-bending competition that will put your creative thinking and technical skills to the test!

Get ready to unleash your inner hacker as you dive into a virtual playground of domains, armed with APIs, tools, and your coding prowess. 

More info here: [Contest Info]([https://github.com/ReconVillage/reconaacharya/blob/main/all_valid_subdomains_keyword_sorted](https://reconvillage.org/the-recon-aacharya-contest-find-subdomains-like-a-pro/))

## Datasets-Released

This repository contains a collection of datasets that are invaluable for subdomain enumeration and analysis. Below is a brief description of each dataset:

### Subdomain Lists

- [`all_valid_subdomains_keyword_sorted`](https://github.com/ReconVillage/reconaacharya/blob/main/all_valid_subdomains_keyword_sorted): A sorted list of all valid subdomains based on keywords.
- [`domains.txt`](https://github.com/ReconVillage/reconaacharya/blob/main/domains.txt): A list of root domains.
- [`valid_subdomains.txt`](https://github.com/ReconVillage/reconaacharya/blob/main/valid_subdomains.txt): A list of valid subdomains.

### Keyword-Based Datasets

- [`all_valid_subdomains_keywords_splitted_sorted`](https://github.com/ReconVillage/reconaacharya/blob/main/all_valid_subdomains_keywords_splitted_sorted): Sorted list of valid subdomains with keywords split.
- [`subdomain_keywords_all_uniq_count`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_all_uniq_count): Unique keyword count across all subdomains.
- [`subdomain_keywords_splitted_all_uniq_count`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_splitted_all_uniq_count): Unique count of split keywords across all subdomains.

### Top Keywords

- [`subdomain_keywords_splitted_top100`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_splitted_top100): Top 100 split keywords.
- [`subdomain_keywords_splitted_top1000`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_splitted_top1000): Top 1000 split keywords.
- [`subdomain_keywords_splitted_top10000`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_splitted_top10000): Top 10,000 split keywords.
- [`subdomain_keywords_splitted_top100000`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_splitted_top100000): Top 100,000 split keywords.
- [`subdomain_keywords_top100`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_top100): Top 100 keywords.
- [`subdomain_keywords_top1000`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_top1000): Top 1000 keywords.
- [`subdomain_keywords_top10000`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_top10000): Top 10,000 keywords.
- [`subdomain_keywords_top100000`](https://github.com/ReconVillage/reconaacharya/blob/main/subdomain_keywords_top100000): Top 100,000 keywords.

Feel free to explore these datasets for your research or operational needs.

# Instruction to submit your `subdomains.txt` :
   * `curl --request PUT --upload-file subdomains.txt "YOUR_UNIQUE_SIGNED_URL"` 
# Reconaacharya Challenge Defcon 31: Rules of the game!
1. **Challenge Submission**: You would have received an email instructions on your registered email to submit the valid submissions. Use your unique AWS S3 signed URL to upload your submissions.
2. **File Submission Rules:**
    * **Filename:** The file containing your subdomains should be named `subdomains.txt`. 
    * **New Line Separation:** When entering subdomains in the submission file, each one should be placed on a new line.
    * **DNS Resolution:** All subdomains you list must be resolvable from Google's public DNS server (8.8.8.8).
    * **Valid Records:** Each subdomain must have a valid DNS record. This can be an 'A' record, a 'TXT' record, or a 'CNAME' record or 'MX' record.
    * **Off-Target Subdomains:** If you include subdomains that are not within the target domains, they will be treated as invalid and potentially face penalties.
    * **Wildcard Subdomains:** Subdomains that use wildcards (e.g., `*.example.com`) are not permitted.
    * **File Size Limit:** The size of your `subdomains.txt` file should not exceed 25MB.

6. **Mandatory Writeup:** Along with your list of subdomains, a writeup explaining your findings and methodologies is mandatory.
7. **Transparency:** All the listed subdomains will be made public once the challenge is over.
8. **Invalid Subdomains Penalty:** If your list contains an excessive number of invalid subdomains (beyond a set limit), you will be banned from the challenge.
10. **No Attacking:** Do not launch any attacks on the listed domains or subdomains. This challenge is purely for discovery and enumeration, not exploitation.
11. **Subdomains submission:** You are allowed to upload only 100 valid files. Any files uploaded beyond this number will not be considered.

**Violation of any of the above rules can lead to disqualification from the Reconaacharya challenge. Ensure to follow the rules diligently.**

## Reconaacharya Event Time:

**Start Time:** 11th August, 2023, 10AM PDT  
**End Time:** 12th August, 2023, 11:59PM PDT
