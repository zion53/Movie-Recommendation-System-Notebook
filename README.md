# Movie-Recommendation-System-Notebook

## 📖 Overview  
This project implements a **Hybrid Recommendation System** by combining multiple methodologies:  
1. **Genre-Based Recommendations**: Content-based filtering using cosine similarity on genre features.  
2. **Popularity-Based Recommendations**: Highlights popular items using ratings and frequency.  
3. **Collaborative Filtering**: Uses user-item interaction data and pairwise similarity to generate recommendations.  
4. **K-Nearest Neighbors (KNN) Model**: Identifies similar users or items based on a sparse matrix.  
5. **Hybrid System**: Combines the strengths of the above techniques with configurable weights for personalization.

---

## 🛠 Features  
- **Genre-Based Recommendation**: Leverages cosine similarity for recommending items with similar genres.  
- **Popularity-Based Recommendation**: Prioritizes items with high average ratings and popularity metrics.  
- **Collaborative Filtering**: Calculates user and item similarity matrices using pairwise distances.  
- **KNN for User Similarity**: Implements KNN on a sparse matrix for user-item recommendations.  
- **Hybrid System**: Integrates genre, popularity, and collaborative methods using weighted factors for optimized results.  

---

## 🔧 Implementation Details  

### 1. Data Preprocessing  
- **Data Cleaning**: Combined and refined raw datasets for effective processing.  
- **Matrix Creation**: Built a sparse user-item matrix to reduce memory usage.

### 2. Genre-Based & Popularity-Based Recommendations  
- **Genre Similarity**: Computed cosine similarity between genre vectors.  
- **Popularity Metric**: Calculated average ratings and frequency for prioritizing items.

### 3. Collaborative Filtering  
- **User & Item Similarities**: Constructed similarity matrices using pairwise distances.  
- **Subset Usage**: Used 5% of the dataset to improve computational efficiency.  

### 4. K-Nearest Neighbors (KNN) Model  
- **Training**: Trained on a 943x1682 sparse matrix using cosine distance.  
- **Thresholding**: Limited recommendations to those with high similarity scores.  

### 5. Hybrid Recommendation System  
- **Integration**: Combined genre, popularity, and collaborative filtering with configurable weights.  
- **Weighted Factors**: Enabled tuning for personalized recommendations.

### 6. Evaluation  
- **Metric**: Root Mean Square Error (RMSE) to assess performance.  
- **Results**: Error metrics helped refine the hybrid model's accuracy.

---

## 📊 Results  
- **Improved Similarity Metrics**: KNN with cosine distance enhanced user similarity computations.  
- **Diverse Recommendations**: Content-based and popularity filtering ensured a variety of suggestions.  
- **Personalized Recommendations**: Weighted hybrid model yielded a balanced recommendation list.  

---


