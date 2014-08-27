   _____ _               _____ _____ ______ _____         
  / ____| |        /\   / ____|_   _|  ____|  __ \        
 | |  __| |       /  \ | |      | | | |__  | |__) |       
 | | |_ | |      / /\ \| |      | | |  __| |  _  /        
 | |__| | |____ / ____ \ |____ _| |_| |____| | \ \        
  \_____|______/_/    \_\_____|_____|______|_|__\_\_____  
 | |  | |  __ \| |    / __ \   /\   |  __ \|  ____|  __ \ 
 | |  | | |__) | |   | |  | | /  \  | |  | | |__  | |__) |
 | |  | |  ___/| |   | |  | |/ /\ \ | |  | |  __| |  _  / 
 | |__| | |    | |___| |__| / ____ \| |__| | |____| | \ \ 
  \____/|_|    |______\____/_/    \_\_____/|______|_|  \_\
                                                          
                                                          
----------------------------------------------------------
(c) 2014 EdgeCase, Inc.  All Rights Reserved.
    Sam Caldwell [sam@edgecase.io]
--------------------------------------

Purpose:

This utility allows the user to upload files to Amazon Glacier via python 
2.7 via boto.

Usage: 

glacierUpload.py [-h] [--glacierVault VAULT] [--awsKeyId KEYID]
                        [--secret SECRET] [--sourceFile SOURCEFILE]
                        [--description DESC]

uploader for Amazon AWS glacier

optional arguments:
  -h, --help            show this help message and exit
  --glacierVault VAULT  AWS Glacier Vault URI
  --awsKeyId KEYID      AWS API Key Id (aws_awsKeyId)
  --secret SECRET       AWS secret (aws_secret_access_key)
  --sourceFile SOURCEFILE
                        Source file to be uploaded.
  --description DESC    optional description.

