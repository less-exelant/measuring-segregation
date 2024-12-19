## Metric Formulations

### **Evenness Metrics**

#### **Dissimilarity Index**
\[
D = 0.5 \sum_{i=1}^{n} \left| \frac{P_{white, i}}{P_{total, i}} - \frac{P_{white, region}}{P_{total, region}} \right|
\]
- **Definition**: Proportion of one group that would need to relocate to achieve uniform distribution.
- **Interpretation**: Ranges from 0 (perfect integration) to 1 (perfect segregation).

---

#### **Gini Coefficient**
\[
G = \frac{\sum_{i=1}^{n} \sum_{j=1}^{n} |P_{i} - P_{j}| \cdot W_{i} \cdot W_{j}}{2 \cdot (\sum_{i=1}^{n} W_{i})^2 \cdot \bar{P}}
\]
- **Definition**: Quantifies inequality in the distribution of groups across areas.
- **Interpretation**: Higher values indicate more segregation.

---

#### **Entropy Index**
\[
E_{local, i} = - \sum_{g} \left( P_{g, i} \cdot \log(P_{g, i}) \right)
\]
\[
E_{index} = 1 - \frac{E_{local, i}}{E_{region}}
\]
- **Definition**: Deviation of local diversity from regional diversity.
- **Interpretation**: Values closer to 1 indicate segregation.

---

#### **Atkinson Index**
\[
A = 1 - \left( \frac{\sum_{i=1}^{n} (P_{g, i})^{1-\epsilon}}{n} \right)^{\frac{1}{1-\epsilon}}
\]
- **Definition**: Measures representation of groups, adjustable for sensitivity (\(\epsilon\)).
- **Interpretation**: Ranges from 0 to 1; higher values indicate segregation.

---

### **Exposure Metrics**

#### **Interaction Index**
\[
I = P_{white, i} \cdot P_{black, i}
\]
- **Definition**: Likelihood of interaction between majority and minority groups.
- **Interpretation**: Lower values indicate reduced interaction.

---

#### **Isolation Index**
\[
Iso = (P_{black, i})^2
\]
- **Definition**: Likelihood of minority interaction within their own group.
- **Interpretation**: Higher values indicate greater isolation.

---

#### **Correlation Ratio**
\[
\eta^2 = Iso - I
\]
- **Definition**: Adjusted isolation index accounting for population proportions.
- **Interpretation**: Higher values indicate stronger segregation.

---

### **Concentration Metrics**

#### **Delta Index**
\[
\Delta = \frac{1}{2} \sum_{i=1}^{n} \left| \frac{P_{black, i}}{P_{total, i}} - \frac{P_{black, region}}{P_{total, region}} \right| \cdot \frac{P_{i}}{P_{region}}
\]
- **Definition**: Percentage of minority group that must move to achieve uniform density.
- **Interpretation**: Higher values indicate greater segregation.

---

#### **Absolute Concentration**
\[
Abs_{conc} = \frac{P_{black, i}}{\max(P_{black, i})}
\]
- **Definition**: Density of minority group relative to the smallest possible area.
- **Interpretation**: Higher values indicate greater concentration.

---

#### **Relative Concentration**
\[
Rel_{conc} = \frac{P_{black, i}}{P_{black, region}} - \frac{P_{white, i}}{P_{white, region}}
\]
- **Definition**: Density comparison between minority and majority groups.
- **Interpretation**: Positive values indicate minority dominance.

---

### **Centralization Metrics**

#### **Absolute Centralization**
\[
Abs_{cent} = \frac{P_{black, i}}{Distance_{i, center}}
\]
- **Definition**: Minority population proximity to the city center.
- **Interpretation**: Positive values indicate central clustering.

---

#### **Relative Centralization**
\[
Rel_{cent} = \frac{P_{black, i}}{P_{black, region}} - \frac{P_{white, i}}{P_{white, region}}
\]
- **Definition**: Central clustering of minority versus majority populations.
- **Interpretation**: Positive values indicate minorities are closer to the center.

---

### **Clustering Metrics**

#### **Absolute Clustering**
\[
Abs_{clus} = \text{mean}(P_{black, neighbors})
\]
- **Definition**: Minority clustering in contiguous areas.
- **Interpretation**: Higher values indicate stronger enclaves.

---

#### **Relative Clustering**
\[
Rel_{clus} = \frac{Abs_{clus}}{\max(P_{black, i})}
\]
- **Definition**: Comparison of minority clustering relative to their maximum.
- **Interpretation**: Higher values indicate stronger clustering.

---

#### **Spatial Proximity**
\[
SP = \frac{\sum_{j=1}^{k} \frac{1}{d_{ij}} \cdot P_{black, j}}{\sum_{j=1}^{k} \frac{1}{d_{ij}}}
\]
- **Definition**: Average proximity between households weighted by distance.
- **Interpretation**: Higher values indicate closer proximity.

---

#### **Distance Decay Interaction**
\[
DDI = P_{black, i} \cdot e^{-\beta \cdot Distance_{i, center}}
\]
- **Definition**: Interaction probability weighted by distance.
- **Interpretation**: Higher values indicate weaker interaction over distance.

---

#### **Distance Decay Isolation**
\[
DDIso = (P_{black, i})^2 \cdot e^{-\beta \cdot Distance_{i, center}}
\]
- **Definition**: Probability of minority interaction with distance effects.
- **Interpretation**: Higher values indicate stronger isolation.
