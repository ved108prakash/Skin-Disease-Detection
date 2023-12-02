# Skin-Disease-Detection
Overview:-
          This project focuses on the detection of skin diseases using deep learning techniques, specifically employing Convolutional Neural Networks (CNN). The primary objective is to 
           provide an automated system capable of identifying various skin conditions based on images.
Dataset:-
         The project utilizes the Ham10000 dataset, a comprehensive collection of dermatoscopic images containing various skin lesions. The dataset encompasses a diverse range of skin 
         conditions, making it an ideal resource for training a robust skin disease detection model.
Models:-
      1.Sequential API with Conv2D:-
                                    This model employs a sequential architecture using the Conv2D layers for feature extraction.
                                    Achieves an accuracy of 68% on the validation set.
                                    The model serves as a baseline for comparison and understanding the performance of more complex architectures.
      2.MobileNet-V2:-
                                    The MobileNet-V2 architecture is utilized for its efficiency and speed, making it suitable for real-time applications.
                                    Achieves a higher accuracy of 82% on the validation set.
                                    MobileNet-V2 demonstrates improved performance compared to the Sequential API with Conv2D, showcasing the effectiveness of transfer learning.

Training Process:-
                    The models were trained using a combination of data augmentation techniques and transfer learning. Transfer learning involved using pre-trained weights from the 
                          MobileNet-V2 model, which has been proven effective in various computer vision tasks.


How to Use:-
               Requirements:-  
                                  Ensure that the necessary libraries and dependencies are installed. The requirements can be found in the requirements.txt file.

Dataset:-
              Download the Ham10000 dataset and organize it according to the provided instructions in the documentation.


Training:-   
           Download the Ham10000 dataset and organize it according to the provided instructions in the documentation. 
          
           python train.py --model mobilenet
                      Or
           python train.py --model mobilenet

Evaluation:-
             Evaluate the trained models on a test set to assess their performance.
             
             python evaluate.py --model_path path/to/saved/model

Results:-
         The MobileNet-V2 model demonstrates superior accuracy compared to the Sequential API with Conv2D, making it a recommended choice for skin disease detection applications.
               Feel free to explore and modify the code to adapt the project to your specific requirements. 
               If you encounter any issues or have suggestions for improvement, 
               please don't hesitate to reach out.

                          

