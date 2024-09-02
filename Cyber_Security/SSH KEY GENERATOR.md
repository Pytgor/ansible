 # HOW TO CREATE AN SSH KEY 
 In order to create an ssh key your will need to follow the next commands
  
  -==ssh-keygen -t rsa -b 4096 -C "your_email@example.cm"==
  also you can use this command which is a more secure key
   - ssh-keygen -t ed25519 -C "your_email@example.com"

  - ==ssh-add ~/.ssh/id_rsa==
  - ==cat ~/.ssh/id_rsa.pub== (copy this key and paste it in github setting searching for SSH and GPG KEYS)
  - Use ==ssh -t git@github.com== to test your connection 
  - now set your Git username and email following the next steps ==git config --global user.name "Your Name"== and ==git config --global user.email "your_email@example.com"==


  
  
