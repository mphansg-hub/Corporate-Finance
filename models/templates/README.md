# models/templates/

This directory contains the instructor-provided Excel template used as the 
foundation for all financial modeling work in BUS-629.

## File

| File | Description |
|------|-------------|
| `performance-ratios-template.xlsx` | Unmodified instructor template — do not edit directly |

## Template structure

| Tab | Contents |
|-----|----------|
| Cover & Instructions | Project overview and named-range key |
| Legend | Color-coding: yellow = inputs, blue = assumptions, green = formulas, gray = outputs |
| Income Statement | Line items with named-range placeholders (`INC_*`) |
| Balance Sheet | Current and prior year columns (`BAL_*`, `startYear_*`) |
| Cash Flow | Operating, investing, financing activities (`CASH_*`) |
| Ratios | Six ratio categories, fully formulaic (`RATIO_*`) — auto-populates at Stage 3 |

## Usage convention

- This file is **read-only** at Stage 1 — uploaded unmodified per assignment instructions
- At Stage 3, a populated copy will be placed in `../builds/` with the company name in the filename
- Do not hardcode numbers into the Ratios tab — all values derive from named ranges in the financial statement tabs

## Stage reference

| Stage | Action |
|-------|--------|
| Stage 1 | Upload unmodified template here ← current |
| Stage 3 | Populate financials; save populated copy to `models/builds/` |
| Stage 4 | Reference named-range conventions when writing LLM specs |
