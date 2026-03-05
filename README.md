# Asthma-Detection-System
ML project to detect asthma and other respiratory diseases using audio spectrograms

Project Title: Asthma Detection from Audio.

Dataset Source: Mention it uses the "Asthma Detection Dataset Version 2" from Kaggle.

Requirements: List the libraries used, such as librosa, torch, numpy, and pandas.

⏩ Mel-Spectrogram Visualizations
🎧 Visualizing one example from each category:

healthy example:
<img width="1489" height="989" alt="image" src="https://github.com/user-attachments/assets/02224ca0-fa1a-4c66-90e6-80608f54c4ae" />

pneumonia example:
<img width="1489" height="989" alt="image" src="https://github.com/user-attachments/assets/4b740e35-f0cd-4c90-bc39-fbb6cbe4e9bc" />

copd example:
<img width="1489" height="989" alt="image" src="https://github.com/user-attachments/assets/65fe05bd-6ec3-4534-ab81-56dca3b756c6" />

asthma example:
<img width="1489" height="989" alt="image" src="https://github.com/user-attachments/assets/ed646f45-647f-4e94-bfef-dd9e1ea17826" />

Bronchial example:
<img width="1489" height="989" alt="image" src="https://github.com/user-attachments/assets/d1266822-467e-460e-bafa-7fc0ae06feae" />


⏩ A batch from the training loader:
Sample batch from training loader:
Features shape: torch.Size([4, 128, 256])
Lengths: tensor([256, 256, 256, 256])
Labels: tensor([1, 2, 1, 1])

<img width="908" height="590" alt="image" src="https://github.com/user-attachments/assets/a2f3f2bf-7097-4179-a497-595456099e3e" />


⏩ Dataset Class Balance:

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/47b3fd72-f54c-499a-abcd-d1943848606f" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/fded1e54-eb55-4c19-81ea-5e1cc5195be1" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/5b3de430-f39c-4d1b-ad32-97e9e67aed7f" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/071cd167-3012-4a42-8f73-dd4013a4cf65" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/c53888be-516a-4afd-9d19-93c95742e93c" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/9f322f60-448c-4f85-a61d-283dbcb488c9" />
<img width="1008" height="855" alt="image" src="https://github.com/user-attachments/assets/fb1b9765-db71-4764-a8e0-f6c13d91b501" />



⏩ Training History:

<img width="691" height="547" alt="image" src="https://github.com/user-attachments/assets/1f59e8f4-9ca0-408e-97c5-9b4ec974182c" />
<img width="846" height="701" alt="image" src="https://github.com/user-attachments/assets/b143004b-c489-4e73-ad9a-a29a2c194be3" />
<img width="857" height="701" alt="image" src="https://github.com/user-attachments/assets/fbf34d35-2c97-4871-9a05-6d6e292f807a" />
<img width="567" height="506" alt="image" src="https://github.com/user-attachments/assets/10c3dba1-1471-442d-a987-7132f7be12a4" />
<img width="691" height="547" alt="image" src="https://github.com/user-attachments/assets/9bc7b218-0d3e-4ad9-8ee2-0befc935783e" />
<img width="846" height="547" alt="image" src="https://github.com/user-attachments/assets/ca2ad6d7-d512-4565-aaa6-1e0be8a502aa" />
<img width="855" height="547" alt="image" src="https://github.com/user-attachments/assets/1ab9e34e-102f-4f6c-8ab5-6abed2facf58" />
<img width="567" height="506" alt="image" src="https://github.com/user-attachments/assets/b55dd8ec-0bda-4005-9064-2d8a7b1db89f" />
<img width="846" height="624" alt="image" src="https://github.com/user-attachments/assets/caa1507f-bd17-4944-a2d1-bea537bb1256" />








