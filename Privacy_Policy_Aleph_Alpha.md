Aleph Alpha Privacy Policy
Last Updated: September 28, 2025
This Privacy Policy describes how Aleph Alpha ("we," "us," or "our") handles information when you use our macOS application. Your privacy and the security of your data are critically important to us.
In Short
To perform its core function, Aleph Alpha sends the content of your selected PDF documents directly from your computer to third-party AI services for processing. Aleph Alpha operates without its own servers, meaning we never receive, see, or store your document content. The application acts as a secure bridge between your files and the AI model you select. Your personal API keys are stored securely on your computer in the macOS Keychain.
1. Data Processing and Third-Party Services
a. PDF Document Content:
The primary function of Aleph Alpha is to extract data from PDF documents using Large Language Models (LLMs). To achieve this, the application reads the text content (such as paragraphs, tables, and lists) from the documents you select on your device. This content is then transmitted over the internet directly from the application to the third-party AI provider associated with the model you choose in the app's settings.
b. Third-Party AI Providers:
We integrate with various external AI providers to offer a wide range of data extraction capabilities. These providers may include but are not limited to:
OpenAI
Google
Anthropic
Mistral AI
Other providers available through LiteLLM
We do not control the data privacy practices of these third parties, as their services operate independently. Because Aleph Alpha does not have a server, your data is never routed through or stored by us. We strongly advise you to review the privacy policies of the respective AI providers before processing documents containing sensitive information, as their data retention and usage policies are outside of our control.
c. Redaction of Sensitive Information:
Aleph Alpha includes a feature that allows you to specify sensitive values (e.g., names, email addresses, or company-specific terms) to be removed from the raw text before it is sent to the third-party AI provider. This redaction occurs entirely on your device, providing you with an important layer of privacy control.
Important Limitation: This feature is highly effective but only applies to extracted plain text. If you use a vision-enabled AI model (one that can analyze images), any sensitive information contained visually within images, charts, or scanned portions of your PDF will not be redacted. This is because the text is part of the image's pixel data and cannot be removed by our text-based tool. For instance, if a scanned receipt image contains a credit card number, the redaction tool will not be able to remove it from the image data sent to a vision-enabled model.
2. Information We Collect
a. License Information:
To activate and validate an Aleph Alpha Pro license, we verify your license key with our payment processor, Gumroad. This is a standard procedure to prevent fraud and ensure that Pro features are unlocked for valid license holders. This process may involve sharing your license key with Gumroad to confirm its validity.
b. Anonymous Analytics (Optional):
We may collect anonymous and aggregated usage statistics to help us identify bugs, improve application performance, and understand which features are most used. This data is strictly non-personal and does not include any content from your documents. Examples of such data include app crash reports, the popularity of certain AI models, or how often a feature is used. This helps us focus our development efforts on improving the app for everyone.
3. Data Security
a. Secure Transmission:
All data, including your document content, is transmitted to and from third-party AI services using encrypted HTTPS connections. This industry-standard protocol ensures that the data is scrambled and cannot be easily intercepted while in transit between your computer and the AI provider.
b. Secure Storage of API Keys:
Your personal API keys for third-party services are never transmitted to us or stored anywhere other than your own computer. They are stored securely in the macOS Keychain, the standard, encrypted storage system provided by Apple. This means only you and applications you explicitly authorize on your Mac can access them, providing a robust layer of protection against unauthorized use or theft.
4. User Consent
Before any data is sent to a third-party AI service for the first time, Aleph Alpha will present you with a mandatory confirmation dialog. This dialog explains the data-sharing process and requires your explicit consent before you can proceed. This initial step is crucial for ensuring you are fully informed. By granting consent, you confirm that you have read our policies and agree to take responsibility for the documents you choose to process through third-party services.
5. Your Rights
Aleph Alpha is designed to put you in full control of your data workflow. You have the right to choose which documents to process and which AI models to use. You can also manage, update, or remove your API keys at any time from within the application's settings. You always have the right to decline the initial consent, which will limit the app to its offline-only features.
6. Changes to This Policy
We may update this Privacy Policy from time to time to reflect changes in our app or for other operational, legal, or regulatory reasons. We will notify you of any changes by posting the new policy within the application or on our website. For significant changes that affect how your data is handled, we will provide a more prominent notification.
7. Contact Us
If you have any questions or suggestions about our Privacy Policy, please do not hesitate to contact us at:

