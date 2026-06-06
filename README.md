# Tsunami vulnerability functions

## Overview

This dataset provides tsunami vulnerability functions for structures commonly found in industrial sectors in port areas. The vulnerability functions describe the relationship between tsunami inundation depth and loss ratio. The loss ratio is defined as the ratio of estimated repair cost to the replacement cost of a structure. The loss ratios were developed using data from port structures damaged during the 2011 Tōhoku tsunami in the Tohoku region, Japan. The vulnerability functions were derived following the methodology presented in Miki et al. (2025), *A proposed approach towards minimizing basis risk in tsunami parametric insurance schemes*.

The dataset is stored as spreadsheets in `.xlsx` format and is compatible with Microsoft Excel, Python, R, and other statistical software. It is intended for applications in disaster risk assessment, insurance, and catastrophe risk modeling.

This dataset is provided courtesy of the International Research Institute of Disaster Science (IRIDeS), Tohoku University. The data may be used freely with proper citation and/or acknowledgment.

---

## Data Description

The loss ratios were developed for eight common port industries (see table below) identified along the coast of Japan's Tohoku region, as described in Chua et al. (2021). These loss ratios may also be applicable to ports and industries in other regions exposed to tsunami hazards.

The dataset separates loss ratios into two structural types—buildings and non-building infrastructure—across two spreadsheets. Loss ratios are further grouped by industry sector. The values represent mean loss ratios and do not include uncertainty ranges.

An explanation of the labels used in the dataset is provided in the table below.


<table>
  <thead>
    <tr>
      <th>Label</th>
      <th>Sub-label</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Tsunami intensity measure</td>
      <td>Inundation depth</td>
      <td>Tsunami inundation depths in meters</td>
    </tr>
    <tr>
      <td rowspan="8">Industrial sectors loss ratio</td>
      <td>Construction material industry</td>
      <td rowspan="8">Mean loss ratios by industrial sector at 0.01 m intervals. The values range between 0 and 1.</td>
    </tr>
    <tr><td>Cargo handling industry</td></tr>
    <tr><td>Chemical industry</td></tr>
    <tr><td>Food industry*</td></tr>
    <tr><td>Manufacturing industry</td></tr>
    <tr><td>Petrochemical industry</td></tr>
    <tr><td>Energy-related industry</td></tr>
    <tr><td>Warehousing and distribution*</td></tr>
  </tbody>
</table>

\* Infrastructure-specific vulnerability functions are not provided for the food industry and warehousing and distribution sector due to insufficient sample sizes.

---

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

## Citation

If you use this dataset, please cite the following publication:

> Miki, Y., Chua, C. T., Suppasri, A., Cheng, A. C., Iwasaki, T., Shinozuka, Y., Takafumi, O. & Imamura, F. (2025). A proposed approach towards minimizing basis risk in tsunami parametric insurance scheme. *npj Natural Hazards*, 2(1), 67.

---

## Acknowledgements

This dataset was developed as part of a collaborative research project with Swiss Re International SE, Japan Branch. The structural damage probability data used to generate the vulnerability functions was provided by Constance Chua, with funding from SCOR Reinsurance Asia-Pacific.

---

## Disclaimer

The authors are not responsible for any decisions or outcomes resulting from the use of this dataset.

---

## References

Miki, Y., Chua, C. T., Suppasri, A., Cheng, A. C., Iwasaki, T., Shinozuka, Y., Takafumi, O. & Imamura, F. (2025). A proposed approach towards minimizing basis risk in tsunami parametric insurance scheme. *npj Natural Hazards*, 2(1), 67.

Chua, C. T., Switzer, A. D., Suppasri, A., Li, L., Pakoksung, K., Lallemant, D., Jenkins, S. F., Charvet, I., Chua, T., Cheong, A. & Winspear, N. (2020). Tsunami damage to ports: cataloguing damage to create fragility functions from the 2011 Tohoku event. *Natural Hazards and Earth System Sciences Discussions*, 2020, 1–37.
