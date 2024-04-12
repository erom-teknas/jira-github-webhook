# JIRA-GitHub Automation Demo 💻🔗

## Overview ℹ️

This project demonstrates automation between JIRA and GitHub. When a JIRA ticket transitions to a specific status, it triggers a GitHub webhook, which then executes a shell script to print the current JIRA ticket ID.

## Technologies Used 🛠️

- JIRA API
- GitHub API
- Shell Scripting

## Setup 🛠️

1. Clone this repository to your local machine.
2. Configure your JIRA and GitHub credentials in the `config.sh` shell script.
3. Ensure that you have the necessary permissions to execute shell scripts.

## Usage 🚀

1. Transition a JIRA ticket to the designated status.
2. GitHub webhook will trigger the execution of the `print_jira_id.sh` shell script.
3. Check the console output to see the current JIRA ticket ID printed by the shell script.


## License 📝

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements 🙏

- This project was inspired by the need for seamless integration between JIRA and GitHub.
- Special thanks to the developers of the JIRA and GitHub APIs for making this integration possible.

## Contact 📧

For any questions or inquiries, please contact [project maintainer's name/email].