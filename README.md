# player-energy-analytics
# Player Energy Spike Analytics

This project analyzes real-time streaming player energy metrics during esports tournaments using the **Sliding Window Technique**.

## Performance Results
- **Naive Algorithm ($O(n \cdot k)$):** Recomputes sub-array sums from scratch, leading to performance degradation on large arrays.
- **Sliding Window Algorithm ($O(n)$):** Uses a running sum by tracking element boundary changes. Runs exponentially faster over thousands of data entries.
