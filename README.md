# Concat Stories

Concat Stories is a Python package that allows you to download Snapchat stories and merge them into a single video file.

## Features

- Download Snapchat stories
- Merge multiple stories into one video
- Easy to use

## Installation

You can install Concat Stories using pip:

```bash
pip install concat-stories
```

## Usage

Here is an example of how to use Concat Stories:

```
usage: concat-stories [-h] -u USERNAME [-o OUTPUT_NAME] [-d] [-w] [-l LIMIT] [-v] [--sleep-interval INTERVAL] [--image-duration DURATION] [--version]

options:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        Snapchat username ex. djkhaled305
  -o OUTPUT_NAME, --output OUTPUT_NAME
                        Output video name ex. dj_khaled_stories
  -d, --delete          Delete stories after download.
  -w, --wait            Wait for user to delete unwanted stories.
  -l LIMIT, --limit-story LIMIT
                        Set maximum number of stories to download.
  -v, --verbose         FFmpeg output verbosity.
  --sleep-interval INTERVAL
                        Sleep between downloads in seconds. (Default: 1s)
  --image-duration DURATION
                        Set duration for image in seconds. (Default: 1s)
  --version             show program's version number and exit
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
