# SafetyPro

Recognize stop signs and other safety-related objects from photos using Microsoft Azure Cognitive Services! Upload an image and find out whether there are safety concerns to be aware of.

- image detection
- computer vision

Sample images are provided in the public/img folder.

I kept the layout intentionally simple because it is a tech demo.

---

## Tech Used

- Machine learning API: Microsoft Azure Cognitive Services
- - Computer Vision
- JavaScript & EJS
- HTML / CSS

## Take-aways / Optimizations

- I learned that Azure's off-the-shelf computer vision counts every road sign as "stop sign".
- This might change or improve over time, and since this app gets classification by API, it will be automatically reflected as changes are made.

Other possible updates may include:

- Use Cognitive Services for OCR, optical character recognition, to read signage
- Recall images from a library
- Open text input to check for custom keywords
- Overlay rectangles over objects, using CSS
- Layout improvements
- Custom vision (supply sample images to train the model, focused on types of road signs)
