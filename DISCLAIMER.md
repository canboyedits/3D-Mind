# 3D-Mind Disclaimer

> [!CAUTION]
> **3D-Mind is an experimental portfolio and research prototype. It is not a medical device, clinical decision-support system, diagnostic service or treatment-planning tool.**

## No medical use

The software, screenshots, model outputs, assistant responses, documentation and visualizations are provided for research discussion, education and technical demonstration only. They must not be used to:

- diagnose, exclude, grade or monitor a tumor or any other condition;
- select, recommend or change medication, diet, surgery, radiotherapy or other treatment;
- replace review of the original MRI by a qualified radiologist or clinician;
- provide an emergency response; or
- make a clinical decision about a real person.

Seek advice from qualified healthcare professionals for all medical questions. In an emergency, contact the appropriate local emergency service.

## Segmentation-model limitations

The tumor mask shown by 3D-Mind is a machine-learning prediction. nnU-Net is a segmentation framework, not a guarantee of correctness. Prediction quality depends on the training data, MRI protocol, input modalities, scanner characteristics, preprocessing, image quality, annotation quality and match between the training population and the evaluated scan.

Possible failures include false positives, false negatives, missing small lesions, incorrect tumor sub-regions, boundary errors, topology errors and failure on data outside the training distribution. A smooth and visually convincing 3D overlay can still be wrong.

No segmentation should be considered clinically reliable without task-specific validation, expert review and the regulatory and quality processes required in the intended jurisdiction.

## Visualization limitations

Rendering changes appearance. Transfer functions, opacity, clipping planes, sampling distance, interpolation, downsampling, compression and lighting can make anatomy or a mask appear larger, smaller, smoother, more solid or less visible. The 3D view is not a replacement for the original diagnostic image series and standard multiplanar review.

Coordinate metadata must be preserved for a valid overlay. A geometry, orientation or resampling error can place a mask in the wrong location even when the scene looks plausible.

## AI assistant limitations

The assistant interface is a prototype. Generated language may be incomplete, outdated, ambiguous or incorrect. It must not invent or interpret diagnoses, prescriptions, appointments or patient records. Any patient-specific information must come from an authenticated, authoritative system and must be clearly distinguished from generated educational text.

Do not rely on assistant output for medical, legal, safety or emergency decisions.

## Privacy and data protection

Do not upload, commit, email or publicly share real patient data, DICOM files, dates of birth, names, record numbers, access tokens or other protected information unless an authorized and compliant environment has been established.

The included screenshots are documentation crops and should be treated as demonstration material. A real deployment would require appropriate de-identification, access control, encryption, audit logging, retention rules, consent, institutional approval and compliance with applicable privacy and health-data law.

Do not send patient data or protected health information to **yashvyas.ofcl@gmail.com**.

## Prototype security

The scan-link and date-of-birth verification interface demonstrates a user experience, not a complete security design. Date of birth alone is generally not a strong authentication factor. A real system would require opaque and revocable access tokens, expiration, authorization, rate limiting, audit trails, secure transport, secret management and a formal threat assessment.

## Third-party software and research

3D-Mind refers to and may depend on third-party libraries, models, standards and publications, including nnU-Net and VTK.js. Those projects retain their own licenses, trademarks, terms and limitations. Inclusion of a reference does not imply endorsement, clinical approval or responsibility by the cited authors or organizations.

## No warranty and limitation of responsibility

The software is provided as-is and without warranty, to the extent permitted by law. See the [LICENSE](LICENSE) for the controlling license terms. Yash Vyas and contributors do not accept responsibility for medical decisions, patient harm, data loss, privacy breaches, security incidents, model errors, visualization errors or other damages arising from use or misuse of this prototype.

## Licensing and commercial use

Repository use is governed by the [PolyForm Noncommercial License 1.0.0](LICENSE) and [NOTICE](NOTICE). Commercial use requires a separate written license from Yash Vyas. A software license governs permissions in the supplied copyrighted work and patent rights covered by the license; it does not by itself create exclusive legal ownership of an abstract idea or research direction.

## Contact

For research collaboration, technical discussion or commercial-licensing inquiries:

**Yash Vyas**  
**Email:** [yashvyas.ofcl@gmail.com](mailto:yashvyas.ofcl@gmail.com)

Do not use this address for medical advice or patient-data transmission.
