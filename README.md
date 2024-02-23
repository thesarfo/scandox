# scandox

this performs document scanning by detecting the contours of a paper in an image and applying a perspective transform to obtain a top-down view. It is useful for digitizing documents, creating PDFs, or performing OCR tasks.

## Usage

1. **Installation**

   - Install the required libraries using pip:
     ```
     pip install -r requirements.txt
     ```
     

2. **Running the Script**


   - Run the script with the `-i` or `--image` argument followed by the path to the image you want to scan:
     ```
     python scan.py -i <path_to_image>
     ```
     Example:
     ```
     python scan.py -i "path/to/your/image.jpg"
     ```

3. **Instructions**

   - The script will display the original image and the edges detected using Canny edge detection.
   - Select an image with clearly defined document edges.
   - Press any key to proceed.
   - The script will then attempt to find the contours of the paper in the image.
   - Once the contours are found, the outline of the document will be displayed.
   - Press any key to proceed with the perspective transformation.
   - The final scanned document will be displayed along with the original image for comparison.


[//]: # (## Note)

[//]: # ()
[//]: # (- Ensure that the image you provide has clear and well-defined document edges for accurate scanning.)

[//]: # (- Experiment with different images and adjust the thresholding parameters if needed for optimal results.)
