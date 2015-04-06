Provides a python fingerprinter class to compute all manner of hashes on files (for now, 'generic' hashes on all files, and Authenticode compliant hashes on PE/COFF files).
Also provides a validator class to check Authenticode signatures.
The plan is to extend this to a wider variety of file hashes and signature validations, primarily targeted at authenticated binaries.