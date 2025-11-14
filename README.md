# ADISA_Enhanced_Machine_Unlearning
This project presents a comparative study of SISA and ADISA for efficient machine unlearning. SISA partitions the dataset into independent shards, enabling partial retraining but suffering from accuracy loss due to random sharding and increased unlearning time with large shards.

ADISA enhances this framework by clustering similar samples using extract_features(), forming coherent data groups that improve learning quality. It further utilizes a teacher–student knowledge distillation process to transfer high-level representations, resulting in higher accuracy and more stable performance. Smaller cluster sizes also significantly reduce unlearning time, making ADISA a practical and scalable solution for real-world machine unlearning systems.
