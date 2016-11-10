---
uid: 
remarks: *content
---
## Remarks  
 For how to write autoscale formulas, see https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/.              This property is required if [Microsoft.Azure.Batch](assetId:///N:Microsoft.Azure.Batch?qualifyHint=False&autoUpgrade=True) is set to true. It must be null if AutoScaleEnabled              is false.  
  
 The formula is checked for validity before the pool is created. If the formula is not valid,              an exception is thrown when you try to commit the [PoolSpecification](assetId:///T:Microsoft.Azure.Batch.PoolSpecification?qualifyHint=False&autoUpgrade=True).