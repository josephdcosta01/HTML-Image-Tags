# HTML-Image-Tags

The <img> tag is used to embed an image in an HTML page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed
Note: Also, always specify the width and height of an image. If width and height are not specified, the page might flicker while the image loads.

The above example shows usage of the <img> element:

The src attribute is required, and contains the path to the image you want to embed.
The alt attribute holds a textual replacement for the image, which is mandatory and incredibly useful for accessibility — screen readers read the attribute value out to their users so they know what the image means. Alt text is also displayed on the page if the image can't be loaded for some reason: for example, network errors, content blocking, or linkrot.

If an error occurs while loading or rendering an image, and an onerror event handler has been set for the error event, that event handler will get called. This can happen in several situations, including:

The src attribute is empty ("") or null.
The src URL is the same as the URL of the page the user is currently on.
The image is corrupted in some way that prevents it from being loaded.
The image's metadata is corrupted in such a way that it's impossible to retrieve its dimensions, and no dimensions were specified in the <img> element's attributes.
The image is in a format not supported by the user agent.
Attributes
