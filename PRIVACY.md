# JoySticky QA Intake — Privacy Policy

**Effective Date:** October 31, 2026  
**Last Updated:** November 1, 2026  
**Application:** JoySticky QA Intake  
**Associated Project:** Project Exhibitionist  
**Privacy Contact:** [eatherdreams@gmail.com](mailto:eatherdreams@gmail.com)

## 1. Overview

JoySticky QA Intake is an automated Discord application supporting the collection, preservation, and technical investigation of player-submitted bug reports for Project Exhibitionist.

The application retains information from an authorized Discord bug-report forum, including relevant replies and accessible archived posts. Forum participants may include reporters, developers, and other people discussing a report. It is not intended to monitor unrelated servers, private messages, or unrelated conversations. Broader Discord event delivery is filtered before unrelated message content is retained for intake.

## 2. Information Collected

The application may process and retain:

- Bug-report message content, relevant discussion context, and previously observed message revisions.
- Discord author identifiers and usernames, and server, forum, thread, message, reply-reference, and attachment identifiers needed to connect evidence with its source.
- Thread titles, owner identifiers, forum tags, archive and lock status, source-message links, and created, edited, and observed timestamps.
- Original attachment filenames, descriptions, content types, file sizes, download or unsupported-file dispositions, and SHA-256 integrity hashes.
- User-submitted diagnostic attachments, including Unity Player.log and Player-prev.log files, diagnostic text, crash dumps, supported ZIP/GZIP archives, and eligible extracted archive members.
- Technical information contained in diagnostics, including hardware specifications, graphics drivers, operating-system details, application errors, and crash context.
- Derived investigation records, diagnostic excerpts, debugger output, candidate corrections, and links between related reports and evidence.

Attachment metadata can be retained even when a file type is unsupported and its contents are not downloaded. Exact duplicate files may share one stored copy while retaining each distinct report or upload occurrence.

Diagnostic files may contain incidental personal information, including system usernames and local file paths. Crash dumps may contain process memory and other sensitive information. Automated screening can quarantine recognizable sensitive patterns, but it does not guarantee that every retained file is free of personal information or secrets.

The private developer workbench uses minimized summaries of reviewed investigations and aggregate intake status. These summaries can include technical diagnoses, candidate corrections, observed hardware information, version provenance, original evidence hashes, case references and links to the relevant Discord report and private GitHub investigation. Such linked summaries are not guaranteed to be anonymous, even when reporter names and raw diagnostic files are omitted.

For workbench sign-in, the application queries GitHub profile and repository-access information to verify authorization. It keeps the authorized viewer's GitHub numeric identifier and login, a session identifier, and the GitHub App user access token in server memory for the sign-in session. The browser receives a secure session cookie rather than the GitHub access token. Hosting and identity providers may also process connection and operational metadata under their own policies.

## 3. Purposes of Processing

Collected information is used to investigate reported technical issues, preserve relevant evidence and provenance, prevent duplicate collection, identify potential failure causes, develop candidate corrections, compare historical behavior, and assist authorized developers with regression verification.

Collected data is not sold or used for advertising or commercial profiling. Collection alone does not establish a diagnosis, a verified fix, or an independently confirmed game build.

## 4. Storage and Security

Collected originals, source metadata, and derived investigation records may be stored on locally managed Windows storage. Eligible evidence may also be stored as assets in a private GitHub repository, along with evidence indexes, technical reports, and issue-tracking records. Local working copies, investigation snapshots, and backups may contain additional copies. This public policy repository does not contain player evidence.

Local evidence uses Windows filesystem access controls, and the evidence repository is private. Access is intended for authorized maintainers and development personnel. Other measures include protected credential storage, encrypted network connections, integrity verification, and screening of eligible evidence before private publication.

The maintainer confirms that BitLocker full-disk encryption is enabled on the Windows volume holding the designated local evidence storage. This is an owner confirmation; the publication audit could not independently read the volume's encryption status. Encryption coverage of any additional storage locations or backups has not been independently verified. Access controls, credential protection, and integrity hashes are not substitutes for encryption at rest.

A separate private website-source repository and a Render-hosted developer workbench may contain minimized reviewed case summaries and aggregate collection metrics. A reviewed baseline is included in the deployed application so that the latest deployed reviewed cases remain available when the local PC is offline or the hosted application restarts. More recent signed updates are held in the running application's memory. The dashboard transfer excludes original logs, crash dumps, diagnostic archives, full Discord message records and local evidence databases.

Case and metric responses require GitHub App authorization for access to the existing private investigation repository. The hosted workbench uses HTTPS and verifies signed updates from the maintainer's local producer. These controls restrict application access but do not make all derived information anonymous or eliminate the hosting provider's role in processing it. The existing statement about owner-confirmed local BitLocker encryption applies to the designated Windows storage; it does not establish encryption coverage or retention guarantees for Render, GitHub, recipient devices or other copies.

## 5. Third-Party Services and AI-Assisted Analysis

Discord and GitHub provide supporting services for message retrieval, evidence delivery and storage, and issue tracking. Authorized maintainers may use OpenAI ChatGPT/Codex to analyze selected diagnostic information and prepare technical investigation reports. Information supplied to these tools is processed by the relevant external service provider.

The maintainers do not collect diagnostic information for the purpose of training or fine-tuning machine-learning models. The collector has no model-training or fine-tuning functionality. AI-assisted investigation is separate from the collector's automatic intake process.

The maintainer confirms that training and data-sharing are disabled for the AI-assisted analysis account. This is an operator confirmation, not an independent audit of the account type, provider settings, or contractual controls. External providers' retention and model-improvement practices depend on their terms, privacy policies, account type, and data-handling settings. This confirmation does not establish zero provider retention or cover other unverified accounts or services.

Render is the selected hosting provider for the private developer workbench. When deployed, it processes its minimized investigation summaries, deployed baseline, signed status updates and sign-in/session information. GitHub also provides identity and repository-access checks for workbench viewers and storage for the separate private website-source repository. Application access is intended for authorized maintainers and developers. Hosting-provider processing is distinct from AI-assisted diagnosis and is subject to the applicable provider terms and data-handling arrangements.

The workbench and its local status producer do not add model-training or fine-tuning functionality. The existing operator confirmation about the analysis account's training/data-sharing settings does not establish settings, contractual controls or retention practices for another provider or account.

## 6. Data Retention

Diagnostic evidence and associated records may remain longer than 30 days when reasonably necessary for ongoing technical investigations, historical comparison, regression analysis, or evidence integrity. The current collector has no automatic evidence-expiry schedule or 30-day purge. Operational storage and transfer limits are not retention deadlines.

Information is retained only while reasonably necessary for the purposes described in this policy, subject to applicable legal and platform requirements, including applicable deletion requests. An investigation or historical record does not by itself override those requirements.

Deleting or editing a Discord message does not automatically remove previously collected messages, observed revisions, attachments, or off-platform copies. Stopping the application or its schedule does not itself erase retained data.

Hosted baseline summaries and their repository history or retained deployment builds can remain until they are deliberately updated or removed through the relevant maintenance and provider processes. Restarting a hosted instance clears that instance's in-memory feed and sign-in sessions; it does not erase the deployed baseline, earlier builds, source-repository history, downloaded briefs or provider-held copies. A viewer session can authorize access for at most eight hours. Expired sessions no longer authorize access and are pruned when authentication state is processed; sign-out removes the relevant local session record. This is not a guarantee of immediate physical memory erasure, an equivalent retention deadline for other copies, or revocation of every provider-side record.

The hosted workbench does not add an automatic 30-day deletion guarantee. Provider-held logs, build artifacts, backups and other residual copies may have different retention arrangements, which maintainers must assess when handling a request.

## 7. Data Deletion and Privacy Requests

Users may request access to, correction of, or deletion of information associated with their submitted reports or personal information by contacting [eatherdreams@gmail.com](mailto:eatherdreams@gmail.com).

Include the relevant Discord report or message link when available, a description of the information concerned, and the requested action. Do not send passwords, bot tokens, recovery keys, or identity documents. A maintainer may request reasonable confirmation of account control or representative authority to verify the request and identify the applicable records.

Requests are reviewed by a maintainer and handled in accordance with applicable legal and Discord platform requirements. The application does not currently offer an automated individual opt-out command or a complete automated deletion workflow. Requests require coordinated manual handling; removing a single local file or source link is not sufficient where copies or shared evidence remain.

Handling a request may require action on local originals, shared duplicate files, containing archives and extracted members, message history and metadata, derived reports, GitHub assets and repository history, working copies, backups, and relevant service-provider copies. Previously collected information must also be considered when preventing recollection from its original source.

The existing tooling cannot guarantee immediate physical erasure from storage remnants, repository history, existing downloads or clones, backups, or third-party systems. Maintainers will communicate the action taken and any remaining copies, limitations, or applicable retention obligations. These technical limitations do not remove applicable deletion obligations. Users should contact the maintainers for requests involving copies outside Discord.

Privacy requests also cover relevant hosted workbench summaries and sign-in information. For a viewer-access request, provide the relevant GitHub account name when appropriate, without sending access tokens or session cookies. A maintainer may request proportionate confirmation of account control. A Discord link, case reference or evidence hash helps locate a record but does not itself establish the requester's authority.

Handling a request may require coordinated changes to authoritative investigation records, the local signed-update queue, the private website-source baseline and its history, running hosted memory, retained deployment builds and relevant provider or developer-held copies. Current tooling does not offer a complete automated deletion workflow. Removing a displayed case or publishing a new baseline does not by itself purge older commits, build artifacts, existing downloads or third-party backups. Maintainers will record the action actually completed and explain any unresolved copies or retention obligations.

## 8. Changes to This Policy

This policy may be updated to reflect changes in the application's functionality, security measures, data-handling practices, or applicable requirements. The latest published version will remain publicly accessible at [this policy URL](https://github.com/JoySticky-Dev-Labs/qa-intake-privacy/blob/main/PRIVACY.md).

## 9. Contact

**JoySticky QA Intake — Privacy and Data Requests**

Email: [eatherdreams@gmail.com](mailto:eatherdreams@gmail.com)

Associated Project: Project Exhibitionist
