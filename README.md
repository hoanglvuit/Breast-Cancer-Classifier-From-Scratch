# Breast Cancer Classifier (From Scratch)

## Mô tả
Xây dựng mô hình phân loại ung thư vú dựa trên bộ dữ liệu `load_breast_cancer`, **tự lập trình hoàn toàn** từ đầu:
- Forward propagation
- Backward propagation
- Gradient Descent

Không sử dụng thư viện huấn luyện như scikit-learn, TensorFlow, PyTorch.

## Công nghệ
- Python
- Numpy (xử lý số liệu)
- Scikit-learn (chỉ để load dữ liệu)

## Dataset
- 569 mẫu, 30 đặc trưng
- 2 nhãn: Malignant (ác tính) và Benign (lành tính)

## Cách chạy
```bash
git clone https://github.com/yourusername/breast-cancer-classifier-from-scratch.git
cd breast-cancer-classifier-from-scratch
pip install numpy scikit-learn
python main.py
