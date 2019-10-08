# Voting Power

In the absense of sufficient time or resources to engage in a full consensus process
the voting process may be considered by an organization as a viable second choice. 

## Calculation

A basic suggested calculation for the voting process is a follows:

```
MemberX_meta_weight = Sum(meta_weights TO MemberX) / Sum(meta_weights) 
MemberX_categoryY_weight = Sum(meta_weights TO MemberX) / Sum(meta-weighted catergory weights FOR CategoryY) 
```

## Calculation Parameters

| Name                | Value    | Description |
| --------------------|:--------:|------------:|
| Max Meta Weight     | 10       | Maximum allowable meta weight |
| Max Category Weight | 100      | Maximum allowable category weight |

## Meta Weights

| From      | To         | Weight    | Comment  |
| ----------|:----------:| ---------:|----------|  
| Member A  | Member A   | 1         |          | 
| Member A  | Member B   | 3         |          | 
| Member A  | Member C   | 100       | ilu      | 
| Member B  | Member A   | 2         |          | 
| Member B  | Member B   | 2         |          | 
| Member B  | Member C   | 2         |          | 
| Member C  | Member A   | 2         |          | 
| Member C  | Member B   | 2         |          | 
| Member C  | Member C   | 2         |          | 

## Category Weights

| From      | To         | Category  | Weight    | Comment   |
| ----------|:----------:| ---------:| ---------:| ---------:|
| Member A  | 1          | 2         | 2         |           |
| Member B  | 1          | 2         | 2         |           |
| Member D  | 1          | 2         | 2         |           |
| Member C  | 1          | 2         | 2         |           |
