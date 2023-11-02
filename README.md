# Introduction to Git and GitHub

## Requirements

1. [Git](https://git-scm.com)
2. [GitHub account](https://github.com/signup)

## Configuration of Git CLI

1. Verify the installation success by running this command:

   ```sh
   git --version
   ```

2. Set your username to match what you've configured on your GitHub account, enclosed within double quotes.

   ```sh
   git config --global user.name "Your GitHub username"
   ```

   Example:

   ```sh
   git config --global user.name "John Joaquin Valdez"
   ```

3. Set your email address to match the one you used to create your GitHub account.

   ```sh
   git config --global user.email your.email@mail.com
   ```

   Example:

   ```sh
   git config --global user.email javaldez1642qc@student.fatima.edu.ph
   ```

## Local Setup

1. Download or clone or this repository by running the command:

   ```sh
   git clone https://github.com/joaquinvaldezzz/git-demo.git
   ```

2. Navigate to the folder using terminal.
3. Verify the proper functioning of your Git CLI:

   ```sh
   git status
   ```
