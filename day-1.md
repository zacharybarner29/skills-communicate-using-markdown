# Daily Learning 

## Morning Planning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">  

1. [ ] make a list
2. [ ] learn different types of lists
  - Unordered
      - Bulleted list
  - Ordered
      - Numbered list
  - Task
      - Checkbox
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
