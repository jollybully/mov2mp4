# Video File Converter

This toolset provides a simple way to re-encode video files in bulk, allowing you to convert or fix multiple video files at once. The scripts currently support .mov and .mp4 formats.

## How to Use

1. Drop your video files into this folder. These files should all be of the same filetype.
2. Double-click on the applicable script (`mov2mp4`, `mp42mov` or `mp42mp4`) to start the conversion process. The script will automatically process all videos in the folder.
3. The converted files will be placed in the `output` folder.

## Scripts

- `mov2mp4`: Re-encodes all .mov files in the folder to .mp4 format.
- `mp42mov`: Re-encodes all .mp4 files in the folder to .mov format.
- `mp42mp4`: Re-encodes all .mp4 files in the folder to .mp4 format again. This can be useful for fixing multiple corrupted or broken .mp4 files at once.
- `mp42mp3`: Converts mp4 to mp3.
- `mp42wav`: Converts mp4 to wav.

## Running Unsigned Scripts on MacOS

If you're running these tools on MacOS, you might encounter security settings that prevent you from running unsigned scripts. Here's how to allow the script to run:

1. After attempting to run the script, go to **System Preferences**.
2. Click on **Security & Privacy**.
3. Select the **General** tab.
4. In the lower half of the window, you should see a message like "'mov2mp4' was blocked from use because it is not from an identified developer."
5. Click the button that says **Open Anyway** next to that message.
6. Confirm the action in the dialog that appears, and the script should run normally, processing all videos in the folder.

Note: The steps above will need to be repeated for each new script you want to run.

For more details about running unsigned scripts on MacOS, you can refer to Apple's official [support page](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/mac).

## Third-Party Software

This project includes FFmpeg, which is used for video and audio processing. FFmpeg is distributed under the GNU Lesser General Public License (LGPL) version 2.1 or later.

### FFmpeg Attribution

FFmpeg is a trademark of Fabrice Bellard, originator of the FFmpeg project.

This software uses libraries from the FFmpeg project under the LGPLv2.1. The source code for FFmpeg can be downloaded from [https://ffmpeg.org/](https://ffmpeg.org/).

For full license details, please see the [FFmpeg License and Legal Considerations](https://ffmpeg.org/legal.html) page.
