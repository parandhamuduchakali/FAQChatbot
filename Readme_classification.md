# README
#### Cat vs Dog Classifier

## Approach
- **Dataset:** Subset of Kaggle’s Cats vs Dogs dataset (adjust path in code).
- **Preprocessing:** Images resized to 150x150 and normalized.
- **Model:** 3 convolutional layers with max-pooling, followed by dense layers.

## Architecture
1. Conv2D(32 filters) → MaxPooling
2. Conv2D(64 filters) → MaxPooling
3. Conv2D(128 filters) → MaxPooling
4. Flatten → Dense(512) → Dropout → Output

## How to Run
1. Download dataset and update the path in the code.
2. Install dependencies: `pip install tensorflow`
3. Run the notebook to train and evaluate the model.