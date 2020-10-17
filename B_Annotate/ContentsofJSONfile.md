
# Contents of this JSON file
JSON data is written as name/value pairs.

A name/value pair consists of a field name (in double quotes), followed by a colon, followed by a value

## shape_attributes
How the Bounding Box is defined, could be a circle, rectangle, etc. The x and y values are the top left corner of the Bounding Box. The width and height is the total width and height of the box

## region_attributes
This contained the label for the region, here 'boots','mask','vest','hardhat'.

## file_attributes
The other extra data like captions, public_domain and urls

{
  "filename": "Image_0.jpg", ==> the name of the file

  "size": 178538, ==>  the size of the image.

  "regions": [

    {
      "shape_attributes": { ==> Shape attribute details for bbox
        "name": "rect",  ==> the type of shape selected for the bbox
        "x": 21,  - x ==> x co-ordinate of top left corner of bbox
        "y": 106, - y ==> y co-ordinate of top left corner of bbox
        "width": 220, ==> width of the bbox
        "height": 429 ==> height of the bbox
      },
      "region_attributes": { ==> region attribute details for boot class
        "class": "boots", ==> attribute  class name for the bbox selection
        "type": "safetygear", ==> attribute conveying type of class
        "image_quality": { ==> attribute conveying image quality
          "frontal": true,  ==> fields conveying the image position
          "good_illumination": true ==> fields conveying the image illumination
        }
      }
    },
    {
      "shape_attributes": {  ==> shape attribute details for bbox
        "name": "rect", ==> the type of shape selected for the bbox
        "x": 512, ==> x co-ordinate of top left corner of bbox
        "y": 315, ==> y co-ordinate of top left corner of bbox
        "width": 225, ==> width of the bbox
        "height": 523 ==> height of the bbox
      },
      "region_attributes": { ==> region attribute details for boot class
        "class": "boots", ==> attribute  class name for the bbox selection
        "type": "safetygear",  ==> attribute conveying type of class
        "image_quality": { ==> attribute conveying image quality
          "frontal": true,  ==> fields conveying the image position
          "good_illumination": true ==> fields conveying the image illumination
        }
      }
    },
    {
      "shape_attributes": {  ==> shape attribute details for bbox
        "name": "rect", ==> the type of shape selected for the bbox
        "x": 819, ==> x co-ordinate of top left corner of bbox
        "y": 266, ==> y co-ordinate of top left corner of bbox
        "width": 282, ==> width of the bbox
        "height": 525 ==> height of the bbox
      },
      "region_attributes": { ==> region attribute details for boot class
        "class": "boots", ==> attribute  class name for the bbox selection
        "type": "safetygear",  ==> attribute conveying type of class
        "image_quality": { ==> attribute conveying image quality
          "frontal": true, ==> fields conveying the image position
          "good_illumination": true  ==> fields conveying the image illumination
        }
      }
    }
  ],
  "file_attributes": {} ==> The other extra data like captions, public_domain and urls
}