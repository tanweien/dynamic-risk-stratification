# Dynamic Risk Assessment Tool
Dynamic risk stratification model predicting mortality in ICU

## Background
It is common for ICU patients to experience a wide range of complications, some of which may be life-threatening, others may resolve on their own.
"Failure to rescue" describes the failure to prevent a death resulting from a complication of medical care or from a complication of underlying illness or surgery.

## Problem statement
We have mature risk prediction scores to estimate mortality in ICU (e.g. APACHE, OASIS)
However the performance of these are lacking (AUC ~0.7) indicating there is a significant number of patients in which prediction is incorrect. The is an opportunity to improve care in patients who are predicted to do well and yet have failure to rescue, who may be better served by early recognition of increased risk.

## Solution
Dynamic risk stratification model predicting mortality (primary) and acute organ failure (secondary)

Dataset: MIMIC IV
