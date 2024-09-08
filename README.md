# Emotion Based Augmented Faces

**Emotion Based Augmented Faces** combines augmented reality with real-time emotion detection to create immersive experience. Using the **MoodMe Emotions Barracuda SDK**, we detect facial expressions and corresponding emotions such as neutrality, sadness, and surprise. Dynamic filters are then applied based on these emotions, enhancing the user’s interaction by augmenting their face with corresponding effects in real-time.  
We leverage **MoodMe’s Emotions Barracuda SDK**, known for its accuracy and fast data processing, to achieve reliable and smooth emotion detection.

## How It Works

- **Facial Pose Recognition and Mesh Tracking**: The project first identifies and tracks the facial pose and mesh using AR techniques to accurately apply augmentations.

- **Real-time Emotion Detection**: Facial expressions are analyzed and classified into one of the supported emotions:
  - Neutral
  - Happy
  - Sad
  - Surprised
  - Angry
  - Afraid
  - Disgusted

- **Dynamic Facial Augmentation**: Based on the detected emotion, a corresponding mask or filter is applied to the face in real-time. As facial expressions change, the augmented face dynamically adjusts, creating a seamless interaction.


## Installation and Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/DouhaSN/Emotion_Based_Augmented_Faces.git

2. Install the required dependencies and SDK (MoodMe Emotions Barracuda).

3. Set up the project in your preferred AR development environment (e.g., Unity).

4. Run the application to begin detecting emotions and applying real-time augmented reality filters.