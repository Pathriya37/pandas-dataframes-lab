# Pandas DataFrames - Lab Practice Sheet

Pandas DataFrames ke 30 practical questions ka lab sheet, Google Colab par banaya hai.

## Sections
- **Section A (Easy):** Q1 se Q15
- **Section B (Moderate):** Q16 se Q25
- **Section C (Hard):** Q26 se Q30

## Topics
- DataFrame banana (dictionary se)
- Columns dekhna (`.columns`)
- Column select karna (`df.Name`, `df['Name']`, `df[['A', 'B']]`)
- Naya column add karna (same value, `np.arange()`, partial `Series`)
- Column delete karna (`del`)
- Column order change karna aur missing column (NaN)
- Space wale column name ko access karna
- `pd.read_clipboard()` se table read karna

## Files
| File | Description |
|------|-------------|
| `pandas_dataframes_lab.ipynb` | Colab notebook (har question ka alag cell, output ke saath) |
| `pandas_dataframes_lab.py` | Same code, normal Python file |

## Kaise run karein
1. `pandas_dataframes_lab.ipynb` ko [Google Colab](https://colab.research.google.com) me kholo
2. `Runtime -> Run all` dabao

Note: `pd.read_clipboard()` Colab/server par clipboard na hone se kaam nahi karta, isliye un cells me sample data se fallback diya hai.

Local me chalane ke liye:

```bash
pip install numpy pandas
python pandas_dataframes_lab.py
```
