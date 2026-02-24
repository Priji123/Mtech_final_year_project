# Mtech_final_year_project
The early identification and assessment of structural cracks in buildings is critical for 
preventing progressive damage and ensuring public safety. Traditional manual inspection 
methods are time-consuming, subjective, and prone to human error, particularly in large
scale infrastructure monitoring. This project presents an Explainable Deep Learning-based 
Crack Detection and Severity Assessment System designed for real-world building 
environments. Unlike existing approaches that are primarily trained on concrete-only 
datasets and focus solely on binary crack classification, the proposed system addresses 
multi-surface building conditions, including plastered walls, painted surfaces, brick 
masonry, and concrete structures. A hybrid deep learning pipeline combining a 
segmentation model (U-Net / YOLO-Seg / SegFormer) and morphological post-processing is 
employed to accurately localize cracks and measure geometric attributes such as length and 
width, enabling severity classification into hairline, moderate, and severe categories. To 
enhance trust and interpretability, Explainable AI (XAI) techniques such as Grad-CAM and 
integrated gradient visualization are integrated to highlight model decision regions and 
differentiate true cracks from noise, shadows, stains, and texture variations. The system is 
trained on a combination of publicly available crack datasets and custom real-world image 
data collected from building environments, enabling robust performance across diverse 
lighting, texture, and surface conditions. Experimental evaluations demonstrate strong 
performance in crack segmentation accuracy, severity estimation, and generalization across 
unseen building surfaces. The proposed solution provides a reliable and transparent tool for 
civil engineers, facility managers, and inspection agencies, paving the way toward 
automated structural health monitoring and safer infrastructure management. 
