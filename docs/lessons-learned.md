# Lessons Learned

- Strong firewall deployments depend on policy intent, not just rule creation.
- Security zones make policy easier to reason about because traffic is controlled by trust boundary.
- NAT must be validated with logs because translation can hide the original troubleshooting context.
- App-ID improves control because applications can use unexpected ports or shared ports such as 80 and 443.
- Security profiles should be attached to allowed traffic so permitted sessions are still inspected.
- URL filtering provides business-friendly control by category, but test evidence is needed to prove enforcement.
- WildFire adds value for unknown-file analysis that traditional signatures may miss.
- User-ID enables role- and group-aware firewall decisions.
- SSL decryption increases inspection depth but requires careful no-decrypt exceptions and certificate trust planning.
- Reporting and logs are part of the implementation, not a separate afterthought.
- Portfolio repositories should separate technical validation screenshots from score or completion screenshots.

