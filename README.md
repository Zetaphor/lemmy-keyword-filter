# Lemmy Post Keyword Filter Userscript

This userscript allows you to filter out posts on Lemmy that match certain keywords. The script adds a settings page to your Tampermonkey menu, where you can specify the keywords to filter. 

If a post's title contains any of the specified keywords, the post will be hidden.

### Installation

### Simple Installation

[Click here to view the script](https://greasyfork.org/en/scripts/471718-lemmy-post-keyword-filter) on Greasyfork.org and install with your userscript extension of choice.

### Manual Installation

1. Install Tampermonkey for your browser of choice.

2. Click on the Tampermonkey icon in your browser's toolbar and select "Create a new script..."

3. Delete the template code that appears, and replace it with the code from userscript.js in this repository.

4. Save the script: File -> Save, or press Ctrl+S.

### Usage

Navigate to any Lemmy website. Click on the Tampermonkey icon in your browser's toolbar, and under the script's name, click on 'Lemmy Keyword Filter Settings'. This will open a settings page where you can enter the keywords you want to filter, separated by commas.

Click the "Save" button to save your keywords and apply the filtering. Posts containing these keywords will be hidden.
Note

The script is set to run on any website, but it will only operate on Lemmy websites. If the script does not detect a Lemmy website, it will not run.

### Written by ChatGPT

Nearly all of this script and README was written by ChatGPT. AI is not going to replace developers, developers that use AI will replace developers.
