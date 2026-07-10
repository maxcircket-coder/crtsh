# crtsh

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/fdfdeda09bc94c86a682c0f1539e0845)](https://app.codacy.com/gh/sksmax/crtsh?utm_source=github.com&utm_medium=referral&utm_content=sksmax/crtsh&utm_campaign=Badge_Grade)

A fast CLI tool for subdomain enumeration using [crt.sh](https://crt.sh) certificate transparency logs.

## Install
```bash
go install github.com/Shaikh-Khizer/crtsh@latest
```

Or build from source:
```bash
git clone https://github.com/Shaikh-Khizer/crtsh
cd crtsh
go build -o crtsh .
```

## Usage
```bash
crtsh <domain>
crtsh <domain> -o output.txt
echo "domain.com" | crtsh
echo "domain.com" | crtsh -o output.txt
```

## Flags

| Flag | Description |
|------|-------------|
| `-o` | Write output to a file instead of stdout |
| `-h` | Show help |

## Examples
```bash
crtsh example.com
crtsh example.com -o subs.txt
echo "example.com" | crtsh -o subs.txt
```
## 📄 License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

---
👨‍💻 Author

***Shaikh Khizer***<br>
Computer Science Student | Penetration Tester
