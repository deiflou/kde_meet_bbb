# kde_meet_bbb

## Download relevant presentation files
Use `kde_meet_download` to download the presentation files.

**Usage**: `kde_meet_download <meeting_id> <download_dir>`

## Make a video from the slides with annotations, mouse cursor and panning/zooming
Use [bbb video download](https://github.com/tilmanmoser/bbb-video-download) to obtain a video from the slides (requires node.js).

The process of transforming the slides data into a video is a bit complex, so there is no custom bash script.

## Make a video from the chat
Use `kde_meet_process_chat` to transform the chat data into a video.

**Usage**: `kde_meet_process_chat <presentation_dir> <output_dir> <video_width> <video_height> <font_face> <font_size>`

**Example**: `kde_meet_process_chat ./pres ./out 400 600 "Liberation Mono" 8`
