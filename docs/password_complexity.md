# Password Complexity




Password requirement checks are implemented in https://github.com/OpenIntegrationEngine/engine/blob/main/server/src/main/java/com/mirth/connect/server/util/PasswordRequirementsChecker.java



Required password complexity is defined in:
https://github.com/OpenIntegrationEngine/engine/blob/main/server/conf/mirth.properties

With properties:
password.minlength = 15
password.minupper = 0
password.minlower = 0
password.minnumeric = 0
password.minspecial = 0
Special characters are defined in the function checkMinSpecial:
https://github.com/OpenIntegrationEngine/engine/blob/a750221ba2eab8be66dcd1bbfa56c70cca025923/server/src/main/java/com/mirth/connect/server/util/PasswordRequirementsChecker.java#L209
