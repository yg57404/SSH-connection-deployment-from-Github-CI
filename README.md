# SSH-connection-deployment-from-Github-CI
SSH connection / deployment from Github CI

Deploy keys on github


You can launch projects from a GitHub repository to your server by using a deploy key, which is an SSH key that grants access to a single repository. GitHub attaches the public part of the key directly to your repository instead of a personal user account, and the private part of the key remains on your server.
Deploy keys with write access can perform the same actions as an organization member with admin access, or a collaborator on a personal repository.


Setup

1. Run the ssh-keygen procedure on your server, and remember where you save the generated public/private rsa key pair.

2. In the upper-right corner of any GitHub page, click your profile photo, then click Your profile.

3. On your profile page, click Repositories, then click the name of your repository.

4. From your repository, click Settings.

5. In the sidebar, click Deploy Keys, then click Add deploy key.

6. Provide a title, paste in your public key.

7. Select Allow write access if you want this key to have write access to the repository. A deploy key with write access lets a deployment push to the repository.

8. Click Add key.


And use File github.yml file.
