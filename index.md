
# Test results

## Word

### DOCX → DOCX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 13805 | 13805 | 13805 |
| Conversion failed | [16](docx-0-CFplus.txt) | 16 ([+1](docx-1-CFplus.txt), [-1](docx-1-CFminus.txt)) | [18](docx-CFcurr.txt) ([+3](docx-2-CFplus.txt), [-1](docx-2-CFminus.txt)) |
| Open failed after conversion | [97](docx-0-OFCplus.txt) | 55 ([+2](docx-1-OFCplus.txt), [-44](docx-1-OFCminus.txt)) | [28](docx-OFCcurr.txt) (±0, [-27](docx-2-OFCminus.txt)) |
| Total succeeded | 13692 | 13734 | 13759 |

### DOC → DOCX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 13688 | 13688 | 13688 |
| Conversion failed | [209](doc-0-CFplus.txt) | 209 ([+1](doc-1-CFplus.txt), [-1](doc-1-CFminus.txt)) | [213](doc-CFcurr.txt) ([+6](doc-2-CFplus.txt), [-2](doc-2-CFminus.txt)) |
| Open failed after conversion | [44](doc-0-OFCplus.txt) | 45 ([+1](doc-1-OFCplus.txt), ±0) | [45](doc-OFCcurr.txt) ([+9](doc-2-OFCplus.txt), [-9](doc-2-OFCminus.txt)) |
| Total succeeded | 13435 | 13434 | 13430 |

### ODT → DOCX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 29487 | 29487 | 29487 |
| Conversion failed | [466](odt-0-CFplus.txt) | 463 (±0, [-3](odt-1-CFminus.txt)) | [469](odt-CFcurr.txt) ([+6](odt-2-CFplus.txt), ±0) |
| Open failed after conversion | [206](odt-0-OFCplus.txt) | 221 ([+21](odt-1-OFCplus.txt), [-6](odt-1-OFCminus.txt)) | [208](odt-OFCcurr.txt) ([+7](odt-2-OFCplus.txt), [-20](odt-2-OFCminus.txt)) |
| Total succeeded | 28815 | 28803 | 28810 |

## Excel

### XLSX → XLSX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 52409 | 52409 | 52409 |
| Conversion failed | [46](xlsx-0-CFplus.txt) | 46 (±0, ±0) | [61](xlsx-CFcurr.txt) ([+15](xlsx-2-CFplus.txt), ±0) |
| Open failed after conversion | [863](xlsx-0-OFCplus.txt) | 835 ([+7](xlsx-1-OFCplus.txt), [-35](xlsx-1-OFCminus.txt)) | [646](xlsx-OFCcurr.txt) ([+1](xlsx-2-OFCplus.txt), [-190](xlsx-2-OFCminus.txt)) |
| Total succeeded | 51500 | 51528 | 51702 |

### XLS → XLSX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 115727 | 115727 | 115727 |
| Conversion failed | [32](xls-0-CFplus.txt) | 31 (±0, [-1](xls-1-CFminus.txt)) | [39](xls-CFcurr.txt) ([+9](xls-2-CFplus.txt), [-1](xls-2-CFminus.txt)) |
| Open failed after conversion | [2239](xls-0-OFCplus.txt) | 2133 ([+34](xls-1-OFCplus.txt), [-140](xls-1-OFCminus.txt)) | [755](xls-OFCcurr.txt) ([+232](xls-2-OFCplus.txt), [-1610](xls-2-OFCminus.txt)) |
| Total succeeded | 113456 | 113563 | 114933 |

### ODS → XLSX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 10624 | 10624 | 10624 |
| Conversion failed | [207](ods-0-CFplus.txt) | 207 (±0, ±0) | [205](ods-CFcurr.txt) ([+2](ods-2-CFplus.txt), [-4](ods-2-CFminus.txt)) |
| Open failed after conversion | [1198](ods-0-OFCplus.txt) | 1196 ([+5](ods-1-OFCplus.txt), [-7](ods-1-OFCminus.txt)) | [824](ods-OFCcurr.txt) ([+16](ods-2-OFCplus.txt), [-388](ods-2-OFCminus.txt)) |
| Total succeeded | 9219 | 9221 | 9595 |

## PowerPoint

### PPTX → PPTX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 1719 | 1719 | 1719 |
| Conversion failed | [1](pptx-0-CFplus.txt) | 1 (±0, ±0) | [1](pptx-CFcurr.txt) (±0, ±0) |
| Open failed after conversion | [54](pptx-0-OFCplus.txt) | 2 (±0, [-52](pptx-1-OFCminus.txt)) | [2](pptx-OFCcurr.txt) (±0, ±0) |
| Total succeeded | 1664 | 1716 | 1716 |

### PPT → PPTX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 2001 | 2001 | 2001 |
| Conversion failed | [18](ppt-0-CFplus.txt) | 18 (±0, ±0) | [19](ppt-CFcurr.txt) ([+1](ppt-2-CFplus.txt), ±0) |
| Open failed after conversion | [37](ppt-0-OFCplus.txt) | 3 (±0, [-34](ppt-1-OFCminus.txt)) | [4](ppt-OFCcurr.txt) ([+1](ppt-2-OFCplus.txt), ±0) |
| Total succeeded | 1946 | 1980 | 1978 |

### ODP → PPTX

|  | 2025&#8209;12&#8209;17 | 2026&#8209;01&#8209;28 | 2026&#8209;02&#8209;07 | 
| :--- | ---: | ---: | ---: |
| Version | 25.04.8.1<br>278cb3481b | 25.04.8.2<br>8d9803cdce | 25.04.9.1<br>7f7ac179 |
| Total tested | 4260 | 4260 | 4260 |
| Conversion failed | [31](odp-0-CFplus.txt) | 31 (±0, ±0) | [34](odp-CFcurr.txt) ([+3](odp-2-CFplus.txt), ±0) |
| Open failed after conversion | [72](odp-0-OFCplus.txt) | 36 (±0, [-36](odp-1-OFCminus.txt)) | [35](odp-OFCcurr.txt) (±0, [-1](odp-2-OFCminus.txt)) |
| Total succeeded | 4157 | 4193 | 4191 |

