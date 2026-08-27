# skaffold-marker-vz7q

Benign Skaffold module used as the test arm of an authorized Cloud Deploy IAM
boundary test in the owner's own GCP project.

It contains a unique marker string (ZZMARKERvz7qQ9WX) so that the tester can
determine whether the content of this repository is actually fetched and
consumed by a render build, rather than merely referenced.

It prints environment information and writes a trivial ConfigMap manifest.
No payloads, no reverse shells, no credential exfiltration, nothing persistent.
