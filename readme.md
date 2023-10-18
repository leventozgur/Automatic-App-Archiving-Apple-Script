
# Automatic App Archiving Apple Script

## Project Description

This project contains an AppleScript script designed to automatically archive Xcode projects and manage the resulting archive files.

## Usage

1. **Preparation:**

   - This script is designed to automatically archive an Xcode project. Before you begin, you need to follow the following preparation steps:
   
     - **Setting the Git URL:** Assign your project's Git repository URL to the `AppURL` variable within the script. The project URL is the link to your project's Git repository.
     - **Defining Project Paths:** Determine the folder paths and file locations used within the script. This specifies where the project is located and the folder paths to access the project.

2. **Running the Project:**

   - When the script is executed, it will follow these steps:
     - Users will be prompted to provide the version number, build number, select the working branch, and choose a scheme.
     - An archive will be created with the specified parameters, and the results will be evaluated.

3. **Monitoring the Results:**

   - The script monitors the success status of the archiving process as it runs through Terminal. In the case of a successful archiving process, the generated archive file will be moved to the download folder, changes will be committed in a new sub-branch, and a notification will be displayed. In case of a failed archiving process, a notification will also be displayed.

4. **Making Code Adjustments:**

   - To adapt this script for your own project, you will need to update variables such as the Git URL and project paths to suit your specific project. Here's how to make these adjustments:

     - `AppURL`: Assign your project's Git repository URL. This is the link to your project's Git repository. For example, `set AppURL to "https://github.com/yourusername/yourproject.git"`
     - Project and file paths: Define the folder paths and file locations used in the project. For example, `set projectFolder to "~/path/to/your/project/"`

## Screenshots

<table>
<tr><img src="https://raw.githubusercontent.com/leventozgur/Automatic-App-Archiving-Apple-Script/main/Screenshots/ss_01.png" alt="ss_01" width="400" style="border: 1px solid;"> </tr>
<tr> <img src="https://raw.githubusercontent.com/leventozgur/Automatic-App-Archiving-Apple-Script/main/Screenshots/ss_02.png" alt="ss_02" width="400" style="border: 1px solid;"> </tr>
<tr> <img src="https://raw.githubusercontent.com/leventozgur/Automatic-App-Archiving-Apple-Script/main/Screenshots/ss_03.png" alt="ss_03" width="400" style="border: 1px solid;"> </tr>
<tr> <img src="https://raw.githubusercontent.com/leventozgur/Automatic-App-Archiving-Apple-Script/main/Screenshots/ss_04.png" alt="ss_04" width="400" style="border: 1px solid;"> </tr>
<tr> <img src="https://raw.githubusercontent.com/leventozgur/Automatic-App-Archiving-Apple-Script/main/Screenshots/ss_05.png" alt="ss_05" width="400" style="border: 1px solid;"> </tr>
</table>

## Requirements

- To run the AppleScript script, you need a Mac computer with Xcode installed.


