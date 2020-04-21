# Datastewardship wizard

## Integration and References
### References
Allows to add references to web pages (URLs), other questions (Cross reference) or chapters and [questions](https://github.com/DSQResources) in the book "Data Stewardship for Open Science : Implementing Fair Principles".
```
Resouce type : Resource Page
Set UUID : abc (code for question)
```

### Integration
Model -> add integration. 
Allows to use an API to other resources for getting actual information.
    * props - filled by DS on model creation, e.g. registry=database, registry=collection in case of fairsharing, depends on the question
    * ItemURL - only URL created and displayed under the answer

```



## Regirstry
For accessing existing knowledge models, it is possible to register local instance into official registry (token based verification)

## DMP vs. Metadata schema
metadata schema is helpful but very rigid
DMP states rather general way how the data will be documented

    * funding
    * responsibilities
    * type of data produced
    * data review
    * data storage and archival
    * ...
