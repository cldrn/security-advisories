# My latest public security advisories

- **CVE-2022-21404**: Applications using Oracle Helidon versions  0.9.x, 0.10.x, 0.11.x, 1.0.x, 1.1.x, 1.2.x, 1.3.x, 1.4.x, 2.0.0-M1, 2.0.0-M2, 2.0.0-M3, 2.0.0-M4 and 2.0.0-RC1 are affected by a remote code execution vulnerability caused by insecure YAML deserialization when using the class UrlConfigSource for loading configuration files remotely. 
- **CVE-2022-23848**: Alluxio 1.6, 1.7, 1.8, 2.0.x, 2.1.x, 2.2.x, 2.3.x and 2.4.x with remote logging enabled using Alluxio Logserver, are affected by a remote code execution vulnerability.
- **CVE-2022-1415**: A flaw was found where some utility classes in Drools core did not use proper safeguards when deserializing data. This flaw allows an authenticated attacker to construct malicious serialized objects (usually called gadgets) and achieve code execution on the server.
- **PWN-2023-01**: A vulnerability was discovered in Microsoft's DICOM implementation. No CVE was issued by Microsoft.
- **PWN-2023-02**: Path traversal & Code Execution in dlopen via environment variable discovered in several open source projects. See [why a comparison between real user id and effective used if is not enough to prevent privilege escalation](https://websec.ca/publication/Blog/comparison-between-real-user-id-and-effective-user-id-is-not-enough-to-prevent-privilege-escalation)
