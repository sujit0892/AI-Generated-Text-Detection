# README for AI Image Dataset

### Dataset Description:
This dataset contains text . The dataset includes various AI generation models such as llama, gpt ,gemma, mistral, qwen , Yi . Text generated has been added to their respective llm model's column name.

### File Structure:
- **`Index`**: A unique identifier for each row in the dataset.
- **`Text`**: Either its a human genereted or AI generated.
- **`Label_A`**: A binary label indicating whether the text is Human(0) or AI-generated(1).
- **`Label_B`**: A label specifying the AI model that generated the text.

### Example Rows:
| Index | Text                                                                       | Label_A | Label_B     |
|-------|----------------------------------------------------------------------------|---------|-------------|
| 0     | The U.S. bombings thatended World War II didn’t mark theclose of atomic ...| 0       | Human_story |
| 1     | The radioactive fallout has led to a spike in thyroid cancers, leukemia ...| 1       | qwen-2-72B  |

### Usage:
This dataset is intended for validating text classification models in two tasks:

Task A: Classifying text as Human or AI-generated.

Task B: Identifying the specific AI model (gemma-2-9b ,mistral-7B ,qwen-2-72B, llama-8B , yi-large and GPT_4-o) used to generate AI text.

Participants will use this dataset to generate predictions for both tasks and submit their predicted labels.