
#QKUBE CLI
QKUBE generator

## Install global
```
- npm install qkube -g 
- yarn global add qkube
```

## Upgrade
yarn global upgrade qkube@latest

## Usage
### Init service
```
mkdir service-a && cd service-a && qkube init service-a
```

## K8s
```
add env: GCP_PROJECT before running k8s generator
```

### Add config
```
qkube config kafka
```

### Add k8s
```
qkube k8s service-a
```



