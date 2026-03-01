# Plant Species Image Classification

# A. Project Overview
This project is an image classification model built using **Google Teachable Machine**.  
It recognizes **20 different plant species** and predicts the flower type from an image.  
The model is intended for educational purposes, gardening reference, and plant identification.

----------------------------------------------------------------------------------------------

# B. Plant Species

# 1. Lily
![images](https://github.com/user-attachments/assets/b4da3480-9fde-454c-8bf8-7dabe6be9275)
- Scientific Name: *Lilium spp.*  
- Description: Large, fragrant flowers that come in various colors.

# 2. Poppy
![000022](https://github.com/user-attachments/assets/7a3eeed4-6ff2-4b82-9e23-50a0702a6401)
- Scientific Name: *Papaver spp.*  
- Description: Bright, colorful flowers often seen in gardens and fields.

# 3. Bougainvillea
![000030](https://github.com/user-attachments/assets/40caade4-1ea1-4ada-abf3-94f7b2e1a1bf)
- Scientific Name: *Bougainvillea spp.*  
- Description: Vibrant climbing plant with papery bracts in various shades.

# 4. Chrysanthemum
![000033](https://github.com/user-attachments/assets/96d5af1c-264f-4975-bfab-27dbcd890369)
- Scientific Name: *Chrysanthemum spp.*  
- Description: Flowering plant known for its large, bushy blooms.

# 5. Ixora
![r](https://github.com/user-attachments/assets/573003ad-d389-4115-aacf-b255a2963e71)
- Scientific Name: *Ixora coccinea*  
- Description: Small, clustered tropical flowers, usually red, orange, or yellow.

# 6. Hibiscus
![000019](https://github.com/user-attachments/assets/6b8b0fdb-d6ae-4279-a298-87f3e27c1cf4)
- Scientific Name: *Hibiscus rosa-sinensis*  
- Description: Large, colorful flowers with a prominent stamen.

# 7. Jasmine
![000025](https://github.com/user-attachments/assets/84054fdf-7ee8-4ba3-8862-74d5a3fefaa9)
- Scientific Name: *Jasminum spp.*  
- Description: Small, white fragrant flowers often used in perfumes.

# 8. Geranium
![000013](https://github.com/user-attachments/assets/c1833ea9-279d-487d-9dc2-f6317ae8426b)
- Scientific Name: *Pelargonium spp.*  
- Description: Garden-friendly plants with vibrant cluster blooms.

# 9. Zinnia
![000015](https://github.com/user-attachments/assets/67e5fb6c-7d59-41cb-a272-05736e41f244)
- Scientific Name: *Zinnia spp.*  
- Description: Bright, daisy-like flowers with long-lasting petals.

# 10. Orchid
![000057](https://github.com/user-attachments/assets/e7a85089-6ff9-49a7-8920-97786ce4b124)
- Scientific Name: *Orchidaceae*  
- Description: Exotic flowers with diverse colors and intricate patterns.

# 11. Marigold
![000106](https://github.com/user-attachments/assets/d8dddd61-7380-4f9d-ac74-439a36f35b70)
- Scientific Name: *Tagetes spp.*  
- Description: Bright orange or yellow flowers commonly used in festivals.

# 12. Cosmos
![000086](https://github.com/user-attachments/assets/c4a6680e-382a-42b7-a112-dc507c91f2d7)
- Scientific Name: *Cosmos bipinnatus*  
- Description: Delicate flowers with daisy-like petals and long stems.

# 13. Tulip
<img width="1200" height="841" alt="000002" src="https://github.com/user-attachments/assets/73c42bfb-76e3-4755-a3e4-0cd3e35d8495" />
- Scientific Name: *Tulipa spp.*  
- Description: Iconic spring flower with cup-shaped blooms in many colors.

# 14. Anthurium
![000042](https://github.com/user-attachments/assets/82fd64cd-f31a-4995-91ca-2b2963f8b6bd)
- Scientific Name: *Anthurium andraeanum*  
- Description: Heart-shaped flowers with glossy spathes and a prominent spadix.

# 15. Daisy
![000009](https://github.com/user-attachments/assets/15e965da-782b-4c9c-ae46-a2ceb06d87ad)
- Scientific Name: *Bellis perennis*  
- Description: Simple, cheerful flowers with white petals and yellow centers.

# 16. Rose
![images (39)](https://github.com/user-attachments/assets/a6c2b948-438a-46fc-a400-11407b33c729)
- Scientific Name: *Rosa spp.*  
- Description: Classic flowers with fragrant petals, available in many colors.

# 17. Sunflower
![000057](https://github.com/user-attachments/assets/04265a76-9224-4e98-8bbf-c5c42db4c895)
- Scientific Name: *Helianthus annuus*  
- Description: Tall flowers with large yellow petals and a dark center.

# 18. Petunia
![000001](https://github.com/user-attachments/assets/ef8014ef-b0da-4f3c-bdf0-04fa10e2955e)
- Scientific Name: *Petunia spp.*  
- Description: Funnel-shaped flowers, commonly used in hanging baskets.

# 19. Lotus
![20](https://github.com/user-attachments/assets/f40486f9-ff60-4d41-a664-ecb843245e45)
- Scientific Name: *Nelumbo nucifera*  
- Description: Aquatic flower with large, fragrant petals and symbolic significance.

# 20. Peony
![wq](https://github.com/user-attachments/assets/ff231013-1e79-476a-bf82-d5f587a8237c)
- Scientific Name: *Paeonia spp.*  
- Description: Large, fluffy flowers with vibrant petals, often fragrant.

----------------------------------------------------------------------------------------------

# C. Model Training Details
- Epochs: 50 → Enough for the model to learn patterns without overfitting too much.
- Batch Size: 16 → Stable training and good balance between speed and accuracy.
- Learning Rate: 0.001 → Standard value that allows steady learning without skipping optimal weights.
- Images per Class: 250

<img width="1919" height="1002" alt="image" src="https://github.com/user-attachments/assets/d46d0cf8-c5b4-4871-82f5-e69cf654f3f0" />

----------------------------------------------------------------------------------------------

# D. Model Evaluation

### Confusion Matrix
<img width="1919" height="1004" alt="image" src="https://github.com/user-attachments/assets/0cfdccc5-6a54-4b50-a3aa-277ebb13231e" />

### Accuracy per Class
<img width="1919" height="998" alt="image" src="https://github.com/user-attachments/assets/9e7133e4-d45a-4e92-8bb7-86d825adef4c" />

### Overall Accuracy
<img width="1919" height="1003" alt="image" src="https://github.com/user-attachments/assets/4fbe0dc3-1b69-40b5-bc51-7a560f905824" />

----------------------------------------------------------------------------------------------

# E. Model Testing

### Test Results
1. Lily - <img width="1919" height="1000" alt="image" src="https://github.com/user-attachments/assets/2d34a203-f1c6-4fbb-bede-0a861a194d75" />
2. Chrysanthemum - <img width="1919" height="998" alt="image" src="https://github.com/user-attachments/assets/cb8aa1a2-0b1b-4a26-963e-a86ffec74acd" />
3. Ixora - <img width="1919" height="1004" alt="image" src="https://github.com/user-attachments/assets/e79057a1-22b5-4f2b-b06c-88eb623f579a" />
4. Jasmine - <img width="1919" height="1006" alt="image" src="https://github.com/user-attachments/assets/e279cfbc-02c2-4bad-aab0-ec6a95ec512d" />
5. Bougainvillea - <img width="1919" height="1002" alt="image" src="https://github.com/user-attachments/assets/abd9a7cb-b88e-4936-bc27-4b950a0fc67e" />
6. Poppy - <img width="1919" height="996" alt="image" src="https://github.com/user-attachments/assets/6b464cf1-c398-4aef-a9b5-d4b80676f3d2" />
7. Zinnia -   <img width="1917" height="984" alt="image" src="https://github.com/user-attachments/assets/f41abba1-9537-4496-a6df-279739f5e022" />
8. Hibiscus - <img width="1919" height="997" alt="image" src="https://github.com/user-attachments/assets/cbc7cf0d-b363-4b39-a815-93202c909003" />
9. Marigold - <img width="1919" height="996" alt="image" src="https://github.com/user-attachments/assets/75128343-a9f5-4a01-a2e4-708c5c6db5b0" />
10. Geranium - <img width="1919" height="1004" alt="image" src="https://github.com/user-attachments/assets/ce7bd6dc-3467-4ebb-b43a-156fd3058ba1" />


----------------------------------------------------------------------------------------------

## Notes
- All images used for testing and training were collected with proper diversity in angles and lighting.  
- The exported model files are included in the repository for further use.
