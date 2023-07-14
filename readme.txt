# Video File Converter

This toolset provides a simple way to re-encode video files into different formats or fix corrupted videos. The scripts currently support .mov and .mp4 formats.

## How to Use

1. Drop your video files (all of the same filetype) into this folder.
2. Double-click on the applicable script (`mov2mp4`, `mp42mov` or `mp42mp4`) to start the conversion process.
3. The converted files will be placed in the same folder.

## Scripts

- `mov2mp4`: Re-encodes .mov files to .mp4 format.
- `mp42mov`: Re-encodes .mp4 files to .mov format.
- `mp42mp4`: Re-encodes .mp4 files to .mp4 format. This can be useful for fixing corrupted or broken .mp4 files.

## Running Unsigned Scripts on MacOS

If you're running these tools on MacOS, you might encounter security settings that prevent you from running unsigned scripts. Here's how to allow the script to run:

1. After attempting to run the script, go to **System Preferences**.
2. Click on **Security & Privacy**.
3. Select the **General** tab.
4. In the lower half of the window, you should see a message like "'mov2mp4' was blocked from use because it is not from an identified developer."
5. Click the button that says **Open Anyway** next to that message.
6. Confirm the action in the dialog that appears, and the script should run normally.

Note: The steps above will need to be repeated for each new script you want to run.

For more details about running unsigned scripts on MacOS, you can refer to Apple's official [support page](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/mac).
