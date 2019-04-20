*Https and ssh are protocols 
https: is always going to verify the server automatically  using certificate authority 
Ssh :  uses Public key authentication ..we need to generate a key-pair which give private and public key .Private key we store in the local and public key we upload to bitbucket.

Using SSH is secure compared with https because keys are more secure than passwords.
To verify the ssh is properly working 
Ssh -T git@bitbucket.org

Pull Request :   Pull request are done by developers bcz developers don’t have merge permissions they rise a pull request and that branch will be reviewed by other developer and approved then the respective branch will be merged with main branches.
*