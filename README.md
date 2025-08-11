# Cat Dataset from TikTok Videos 🐱

There aren’t many datasets that contain multiple images of the same cat from different angles.  
This project does it by:

1. **Scraping TikTok cat videos** and automatically taking multiple screenshots from each.
2. **Running an R-CNN model** (`fasterrcnn_resnet50_fpn`) to detect cats in the screenshots.
3. **Cropping out irrelevant background** so only the cat remains in the picture.

The result is a dataset of ~50 cats, each with multiple images from different positions and sides.
