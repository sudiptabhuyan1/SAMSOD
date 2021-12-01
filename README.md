# Structure-aware multiple salient object detection and localization for autonomous robotic manipulation
This paper proposes a multiple salient region detection and localization approach for unstructured industrial robot work environments with arbitrarily located and orientated objects. Different from the existing, our novel technique to detect multiple salient regions performs locally adaptive center-surround operations on proto-object partitions obtained through color consistency and spatial proximity analysis. The multi-scale center-surround operations are done by masks that are local structure-aware yielding regions with precise and accurate boundaries as required for robotic manipulation. The real-life experiments involving robotic manipulation are carried out to demonstrate the utility of our multiple salient region detection method. For robotic manipulation, object localization is improved after salient region detection by employing a fast shadow detection algorithm proposed based on hue analysis, and recognition through existing matching techniques is applied only at the localized salient regions. 
Proposed approach of multiple salient object detection 
![Figure1_4upload](https://user-images.githubusercontent.com/95354449/144278486-73c9ad82-8d66-4689-9a82-ff706e9533e6.jpg)
Proposed approach of shadow detection 

![Fig4_4upload](https://user-images.githubusercontent.com/95354449/144279895-68331d5a-f308-4aaf-a88e-0bb8b5b04234.jpg)
 Qualitative comparisons
![Capture](https://user-images.githubusercontent.com/95354449/144281750-ad6da316-4249-4aeb-9a24-f7777d263fc7.JPG)


