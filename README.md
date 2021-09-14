# building-footprints-extraction
Extraction of buildings footprints from satellite images
Building footprint extraction is a basic task in the fields of mapping, image understanding and computer vision, etc. Accurately and efficiently 
extracting building footprints from a wide range of remote sensed imagery remains a challenge due to the complex structures, variety of scales and
diverse appearances of buildings. Immediate and accurate building footprint information is significant for illegal building monitoring, 3D building reconstruction,
urban planning and disaster emergency response.Apart from the above examples, building footprints are being used for Geo-marketing, R&D, urban planning, rural development,
policymaking, etc. Clearly, the scope of use for this data is innumerable and only limited by the user‘s imagination. So to counter these problems.Building footprints
extraction is necessary.

Existing convolutional neural network (CNN)-based building extraction methods are criticized for their inability to detect tiny buildings because
 the spatial information of CNN feature maps is lost during repeated pooling operations of the CNN. Additionally, large buildings still have inaccurate segmentation edges.
Moreover, features extracted by a CNN are always partially restricted by the size of the receptive field, and large-scale buildings with low texture are always
discontinuous and holey when extracted. To alleviate these problems, multiscale strategies are introduced in the latest researches to extract buildings with different scales. 
We have used multiple attending path neural network (MAPNet) for accurately extracting multi-scale building footprints and precise boundaries.We used it
 for efficient and accurate multiscale building footprint boundary extraction through parallel localization-preserved convolutional networks.The strategy we
 have used is features extracted from each path were independent with fixed scales, and multi-scale features were only fused at the end of the encoder by attention module.
This algorithm gives better scores and higher accuracy than other algorithms , and provide better results on non pre-trained WHU Datasets.

