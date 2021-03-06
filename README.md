# Terraform Modularisation Example


This repository demonstrates how a simple terraform structure without any modules can be converted into modules.

### Standard structure
```
$ tree standard-structure/
.
├── main.tf
├── variables.tf
├── outputs.tf
```

### Complete Module structure
```
$ tree complete-module/
.
├── main.tf
├── variables.tf
├── outputs.tf
├── ...
├── modules/
│   ├── iam-user/
│   │   ├── variables.tf
│   │   ├── main.tf
│   │   ├── outputs.tf
│   ├── nestedA/
│   ├── .../
├── examples/
│   ├── exampleA/
│   │   ├── main.tf
│   ├── exampleB/
│   ├── .../
```






For more details please refer to - https://www.terraform.io/docs/modules/structure.html


