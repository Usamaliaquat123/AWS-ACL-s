# AWS ACL (Access Control List):

AWS Access control list is written is mostly written in xml similar to like this
```xml
  <?xml version="1.0" encoding="UTF-8">
<AccessControlPolicy xmlns="http://s3.amazonaws.com/doc/2006-03-01">
    <Owner>
        <ID>AWS_OWNER_USER_ID</ID>
        <DisplayName>owner-display-name</DisplayName>
    </Owner>
    <AccessControlList>
        <Grant>
            <Grantee  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                      xsi:type="Canonical User">
                <ID>USER_CANONICAL_ID</ID>
                <DisplayName>display-name</DisplayName>
            </Grantee>
        </Grant>
    </AccessControlList>
</AccessControlPolicy>
```
