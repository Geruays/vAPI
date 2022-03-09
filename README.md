# vAPI v1.0
vAPI is API takes attack data and sends it to one or multiple apis that in the source

### Progress Status

- [ ] Attack System
      
      - [ ] IPv4/URL Validation
      - [ ] Port Validation
      - [ ] Time Validation
- [ ] User Crud/Utils
     - [ ] Crud
     - [ ] Key Validation
     - [ ] Plan Validation
     - [ ] Max time Validation
     - [ ] Conn Validation
     - [ ] Expiry Check
- [ ] Admin Crud/Utils
     - [ ] Read, Add, Remove, Edit User
     - [ ] Read, Add, Remove, Edit APIs
- [ ] Site Protection
     - [ ] Rate Limit (If needed)
     - [ ] Bot Check (Bruteforce etc)


# Installation
```
git clone https://github.com/vlang/v
cd v
make
```
look on the website for more information ``https://vlang.io``
# Supported OS
```
Ubuntu/Debian
```
# Start vAPI
```
v run api.v <api_port>
URL: http://localhost:api_port/api/user=[USER]&host=[HOST]&port=[PORT]&times=[TIME]&method=[METHOD]
```
