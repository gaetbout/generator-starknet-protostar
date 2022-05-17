# <%= projectName %>

### Set up the project

#### Create a Python virtual environment

```bash
python3 -m venv env
source env/bin/activate
```

#### 📦 Install the requirements

```bash
curl -L https://raw.githubusercontent.com/software-mansion/protostar/master/install.sh | bash
```
Then restart the terminal
```bash
protostar install https://github.com/OpenZeppelin/cairo-contracts
```

### ⛏️ Compile

```bash
nile compile --directory src
```

### 🌡️ Test

```bash
# Run all tests
pytest tests
```

## 📄 License

**<%= projectName %>** is released under the [MIT](LICENSE).





