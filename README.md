# TAV---A-Chain-of-Thought-Enhanced-Multi-Hazard-Multi-Modal-Dataset-for-Agent-Intelligence
Most existing remote sensing datasets for disaster assessment primarily contain imagery data, lacking accompanying linguistic instructions or semantic annotations. Even among the few datasets that include textual labels, the format is often limited to simple “Question–Answer (Q–V)” pairs, which fail to capture the reasoning and decision-making mechanisms involved in task execution.

To address this limitation and endow models with autonomous reasoning and external tool-calling capabilities, this project constructs the Chain-of-Thought Enhanced Multi-Hazard and Multi-Modal TAV (Thought–Action–Value) Dataset for Intelligent Agents, based on multi-source remote sensing data and existing vision-language model (VLM) benchmarks.

The dataset consists of two main components: imagery data and fine-tuning instructions. The imagery part integrates diverse samples from remote sensing datasets such as QQB, BRIGHT, GeoBench-VLM, and FloodNet, covering various disaster scenarios and sensing modalities. The fine-tuning instruction part is built upon a unified JSON-based structure, containing high-quality multi-turn “Instruction–Reasoning–Action” records designed to enhance model alignment with intelligent agent training objectives.


<img width="1280" height="470" alt="image" src="https://github.com/user-attachments/assets/e7036b77-32b5-42ba-b0d8-755045e5c16d" />
