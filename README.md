# potato-disease-classifier

Docker commands:
1. docker run -it -v C:\Users\YOGES\Desktop\potato-disease:/potato-disease -p 8501:8501 --entrypoint /bin/bash tensorflow/serving
2. tensorflow_model_server --rest_api_port=8501 --model_name=potato_disease --model_base_path=/potato-disease/saved_models

then run server
FastAPI

then run UI frontend
npm start