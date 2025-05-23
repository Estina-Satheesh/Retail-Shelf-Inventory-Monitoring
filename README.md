TITLE : Retail Shelf Inventory Monitoring.
PURPOSE : The goal is to use deep learning and computer vision to automatically identify and count retail items on a shelf.
          The primary use case is for store managers or retailers to:
               -Keep an eye on product placement.
               - Identify items that are out of stock. 
               - Track the frequency and presence of products on shelves.
TECHNOLOGIES USED :LANGUAGE USED : Python
                   Selected due to its vast ecosystem in deep learning and computer vision.
                   USE OF LIBRARIES AND PACKAGES:
                   The pre-trained YOLOv5 deep learning model is loaded and executed by torch (PyTorch). 
                   CV2 (OpenCV) manages image processing, drawing, and display.
                   OS = File path management, directory collection creation.YOLOv5 uses a counter, which is a simple method of counting detected classes and summarizing pandas, to return results in tabular format 
                   (df)
 USAGE : A technology-driven tool for managing and tracking products on store shelves in real time is a shelf retail inventory monitoring system. Its main purpose is to help retailers prevent stockouts and lost 
         sales by making sure that inventory levels are maintained precisely and that products are displayed appropriately. The system can automatically identify when items are running low or out of stock and 
         notify staff or start restocking procedures by leveraging technologies like RFID tags, Internet of Things sensors, and computer vision. By confirming that products are arranged in accordance with 
         merchandising guidelines, it also guarantees planogram compliance. By keeping an eye on differences between inventory records and shelf contents, these systems can also aid in the detection of theft or 
         shrinkage. Shelf monitoring systems offer insightful information beyond inventory control.
CONCLUSION : After running the code the output will be generated in the following format
             OUTPUT :
                     Annotated image - output/detected_shelf.jpg
                     Detection summary - output/detection_summary.txt


        
