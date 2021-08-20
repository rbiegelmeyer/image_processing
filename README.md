# image_processing

Description.
The package image_processing is used to:

Processing:
- Histogram Matching
- Structural Similarity
- Resize Image

Utils:
- Read Image
- Save Image
- Plot Image
- Plot Result
- plot Histrogram



## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install image_processing

```bash
pip install image_processing
```

## Usage
```python
from image_processing_rbiegelmeyer.utils import io, plot
from image_processing_rbiegelmeyer.processing import combination, transformation

image1 = io.read_image('./data/image1.jpg')
image2 = io.read_image('./data/image2.jpg')

# plot.plot_image(image1)
# plot.plot_image(image2)

result_image = combination.transfer_histrogram(image1, image2)

plot.plot_result(image1, image2, result_image)
```

![alt text](https://github.com/rbiegelmeyer/image_processing/blob/master/doc/Figure_1.png?raw=true)

## Author
Roberto Biegelmeyer
rbiegelmeyer

## License
[MIT](https://choosealicense.com/licenses/mit/)