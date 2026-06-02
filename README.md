# The Official KS4 Engine Website
This is the official KS4 Engine Website. Here you will find these STINKY INSTRUCTIONS on self-hosting it, and what it is for.
## How to self host This Site
Step 1: Fork this repo
Step 2: Change the custom domain and make sure its named [username-or-org].github.io, or you can use the default github domain if you dont have a domain
Step 3: Customize the HTML files to whatever you want and change mirrors to your engine
Step 4: Make checksums for your .PMP files for validating sources
# Making File Hashes
- Windows:
```
Get-FileHash yourproject.pmp -Algorithm SHA256 | Out-File yourproject.pmp.sha256
```
- Linux:
```
sha256sum myfile.txt > myfile.txt.sha256
sha256sum -c myfile.txt.sha256
```
