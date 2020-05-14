# k8s-airflow

## generate fernet key

```shell script
pip install cryptography

python -c "from cryptography.fernet import Fernet; print(Fernet.generate_key().decode())"
```

