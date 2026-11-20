# Step 3: Claim Audit Table
Highlight every sentence of the AI's interpretation from Step 2:
- **Green:** You can recompute it from the data shown.
- **Amber:** It is a possible explanation (not directly recomputable from the summary table alone).
- **Red:** It is a causal claim or refers to data you were not shown.
| Claim (Sentence from AI Interpretation) | Colour (`Green` / `Amber` / `Red`) | How I Checked, Accepted, or Rejected It |
| *Example:* "The mean price increased by 12% from the first to last observation." | Green | Recomputed in `2_work.ipynb` (`(last - first) / first * 100`); accepted because it matched the data. |
| *Example:* "Seasonal supply dips may explain why the mean sits above the median." | Amber | Checked against the summary stats; treated as an unverified explanation (`E`), not a proven fact. |
| *Example:* "A supplier strike caused the spike in week 4." | Red | Rejected as a causal claim (`C`) / unshown external factor not present in the dataset. |
| [Paste sentence 1] | [Green / Amber / Red] | [How you recomputed or evaluated it] |
| [Paste sentence 2] | [Green / Amber / Red] | [How you recomputed or evaluated it] |
# Step 4: Confused Classmate Excerpt
Keep working until the classmate stops repeating the same *"but why?"* confusion about why the mean isn't always the typical price, then paste the key exchange below[cite: 1].
> **Classmate:** The mean is always the typical price—why wouldn't we just use it?
> **You:** [Your explanation using concrete numbers or an extreme/flagged value example]
> **Classmate:** [Follow-up question]
> **You:** [Your clarification]
# Step 5: Reflection
Where did your first draft (`1_attempt.md`) say more than the data allowed?[cite: 1]
- **Overstated claims / unlabelled assumptions:** [Note any sentences in your initial draft that implied causation (`C`) or treated a possible explanation (`E`) as established fact without backing data.]
- **Statistic choice & limitations:** [Note anything your initial draft claimed about "typical" price or trend that required caveats, such as skewness, outliers, or endpoint sensitivity.]
