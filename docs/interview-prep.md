# Interview Prep

## 1. How would you explain this project in an interview?

This project is a controlled-lab enterprise firewall implementation using Palo Alto NGFW concepts. I documented segmentation, policy, NAT, App-ID, threat prevention, URL filtering, WildFire, User-ID, SSL decryption, and reporting as one cohesive security engineering case study.

## 2. What problem do security zones solve?

Security zones define trust boundaries. They make policy easier to manage because rules can control traffic between logical network areas, such as users, servers, acquisition users, management, and the internet.

## 3. How do Security Policy and NAT Policy work together?

NAT changes addressing, while Security Policy decides whether traffic is allowed. During troubleshooting, I would review Traffic logs to confirm the matched security rule, NAT translation, source, destination, application, and action.

## 4. Why is App-ID better than only using ports?

Applications can use common ports like 80 and 443 or change ports. App-ID identifies the application itself, which allows more accurate policy enforcement than simple port-based rules.

## 5. What is a Security Profile Group?

A Security Profile Group bundles inspection profiles, such as Antivirus, Anti-Spyware, and Vulnerability Protection, so they can be applied consistently to allowed Security Policy rules.

## 6. What does URL Filtering add to the firewall?

URL Filtering allows the firewall to permit or block websites by category and risk. It helps enforce acceptable-use rules and block malicious or inappropriate destinations.

## 7. What is WildFire used for?

WildFire analyzes unknown files and suspicious content to identify malware that may not be detected by existing signatures. It strengthens detection for unknown threats.

## 8. What does User-ID provide?

User-ID maps network traffic to users and groups. This allows policies such as permitting a marketing group to specific applications while restricting other users.

## 9. Why is SSL decryption important, and what is the risk?

SSL decryption allows the firewall to inspect encrypted traffic for threats. The risk is privacy and trust impact, so sensitive categories should use no-decrypt exceptions and certificate handling must be planned carefully.

## 10. What evidence would you collect to prove the firewall works?

I would collect Security Policy and NAT screenshots, Traffic logs, Threat logs, URL logs, WildFire verdicts, User-ID logs, decryption logs, ACC views, Dashboard widgets, and custom reports. I would also separate technical validation screenshots from completion-only evidence.

