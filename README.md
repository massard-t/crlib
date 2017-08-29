# crlib
CLI utility providing easier use of C/C++ libraries

## Usage

Simple usage is:

```bash
crlib user/repository
# Will download and extract the HEAD version of the repository, inside repository/
```


You can also _tag_ which version you want to download:
```bash
crlib user/repository:1.0
```

Or even
```bash
crlib user/repository:develop
```
