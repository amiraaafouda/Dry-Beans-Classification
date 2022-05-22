# Dry-Beans-Classification
# Dataset
Given a set of features extracted from the shape of the beans in images and it's required to predict the class of a bean given some features about its shape. There are 7 bean types in this dataset.

# Data fields

- Area - (A), The area of a bean zone and the number of pixels within its boundaries.       
- Perimeter - (P), Bean circumference is defined as the length of its border.       
- MajorAxisLength - (L), The distance between the ends of the longest line that can be drawn from a bean.        
- MinorAxisLength - (l), The longest line that can be drawn from the bean while standing perpendicular to the main axis.    
- AspectRatio - (K), Defines the relationship between L and l.         
- Eccentricity - (Ec), Eccentricity of the ellipse having the same moments as the region.     
- ConvexArea - (C), Number of pixels in the smallest convex polygon that can contain the area of a bean seed.     
- EquivDiameter - (Ed), The diameter of a circle having the same area as a bean seed area.    
- Extent - (Ex), The ratio of the pixels in the bounding box to the bean area.             
- Solidity - (S), Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.           
- Roundness - (R), Calculated with the following formula: (4piA)/(P^2)           
- Compactness - (CO), Measures the roundness of an object: Ed/L           
- ShapeFactor1 - (SF1)         
- ShapeFactor2 - (SF2)          
- ShapeFactor3 - (SF3)        
- ShapeFactor4 - (SF4)          
- Class - the class of the bean. It can be any of BARBUNYA, SIRA, HOROZ, DERMASON, CALI, BOMBAY, and SEKER.        
