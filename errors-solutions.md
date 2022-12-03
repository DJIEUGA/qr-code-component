# error1: Problem accessing my remote repo

fatal: unable to access 'https://github.com/DJIEUGA/qr-code-component.git/': error setting certificate verify locations:  CAfile: E:/Git/mingw64/ssl/certsfatal: unable to access 'https://github.com/DJIEUGA/qr-code-component.git/': error setting certificate verify locations:  CAfile: E:/Git/mingw64/ssl/certs/ca-bundle.crt CApath: none
# solution to error1
executed the command: git config --global http.sslverify "false"