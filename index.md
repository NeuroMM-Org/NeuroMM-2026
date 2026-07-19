# NeuroMM 2026

ACM Multimedia 2026 Workshop and Grand Challenge

## Workshop Title

**The 1st International Workshop on Neurophysiological Intelligence for Human-Aware Multimedia**

NeuroMM treats EEG, ECG, EMG, and wearable biosignals as first-class multimedia modalities and advances cross-modal reasoning with synchronized video, audio, and contextual streams.

---

## Introduction

Multimodal neurophysiological intelligence for human-aware multimedia AI.

### Rationale

Multimedia systems have mainly focused on external perception, including image, video, audio, and language. NeuroMM 2026 expands this scope by integrating internal physiological signals such as EEG, ECG, EMG, and wearable sensing into a unified multimedia framework.

This direction is timely because multimodal foundation models, long-sequence modeling, and sensing infrastructure are converging with clinically grounded data resources. NeuroMM addresses the gap between medical signal interpretation and multimedia reasoning.

The long-term vision is a sustained NeuroMM ecosystem spanning epilepsy analysis, seizure prediction, mental health assessment, sleep analysis, and cardiac monitoring with standardized benchmarks and protocols.

### Focus Areas

- Cross-modal learning with EEG, ECG, EMG and video
- Robust reasoning under artifacts and domain shift
- Neuro-signal foundation models and self-supervision
- Trustworthy and ethical AI for physiological data
- Clinically grounded multimedia benchmarks

---

## News

- **Mar 09, 2026**: NeuroMM 2026 official website launched.
- **Apr 20, 2026 (Planned)**: Challenge data and baseline resources release.
- **Jun 20, 2026 (Planned)**: Result submission opens for challenge tracks.
- **Contact**: Official inquiry email updated: contact@neuromm.org

---

## NeuroMM Grand Challenge

Interictal Epileptiform Discharge Detection and Localization in Multimodal Neuro-Signals.

### Challenge Overview

NeuroMM 2026 reframes epilepsy analysis as multimodal reasoning by integrating EEG-centered physiological data with synchronized contextual information. The challenge is built on vEpiSet, a clinically grounded benchmark collected under standardized protocols.

Dataset highlights include 84 subjects, 20-minute recordings per subject, and 25,449 four-second epochs with expert-reviewed labels, covering both IED and non-IED events under realistic clinical conditions.

### Official Tracks

- **NMM-Basic-IED**: Robust IED detection from heterogeneous physiological signals.
- **NMM-Context-IED**: Vision-enhanced detection with synchronized contextual features.
- **NMM-Source-IED**: Spatial localization of epileptogenic regions across five classes.

### Evaluation Protocol

- Track 1 and Track 2: Primary metric AUPRC, auxiliary metric Precision@Sensitivity=70%.
- Track 3: Primary metric Weighted-F1, auxiliary metric Macro-F1.
- Metrics are designed for severe class imbalance and clinical diagnostic relevance.

### Dataset Snapshot

| Item | Details |
|---|---|
| Subjects | 84 (52 epilepsy, 32 control) |
| Signals | EEG, ECG, EMG, synchronized behavioral context |
| Epochs | 25,449 total (2,516 IED, 22,933 non-IED) |
| Clinical Source | Peking Union Medical College Hospital |

### Link

- View NeuroMM Grand Challenge details: `./challenge.html`

---

## Workshop

The 1st International Workshop on Neurophysiological Intelligence for Human-Aware Multimedia.

### Scope

Multimedia research has traditionally focused on external perception modalities such as images, video, audio, and language. These modalities capture observable behavior, communication, and environmental context, forming the foundation of modern multimedia understanding systems. In contrast, neurophysiological signals, including electroencephalography (EEG), electrocardiography (ECG), electromyography (EMG), and wearable biosensors, encode internal human states related to cognition, attention, emotion, and neural dynamics.

NeuroMM 2026 bridges this divide by introducing Multimodal Neurophysiological Intelligence, a unified computational framework that synergizes heterogeneous physiological signals with synchronized multimedia streams. This approach treats physiological sensing not as a niche medical modality, but as a core extension of multimedia computing for joint reasoning over internal and external human states.

Unlike biomedical or BCI workshops that emphasize isolated neural decoding or clinical pipelines, NeuroMM centers on multimedia-driven neurophysiological reasoning. The workshop aligns with ACM Multimedia by expanding media understanding from external perception toward internal human-state modeling.

A key highlight is the NeuroMM Challenge built on hospital-scale, clinician-annotated synchronized data combining patient monitoring video with EEG, EMG, and ECG. This benchmark targets the real-world problem of distinguishing epileptic discharges from artifacts and noise with multimodal evidence.

Beyond epilepsy detection, NeuroMM aims to establish an ongoing ecosystem covering seizure prediction, mental health assessment, sleep analysis, and cardiac monitoring, with shared tasks, datasets, and evaluation protocols for trustworthy multimodal neuro-intelligence.

### Topics of Interest

#### Foundations & Core Methodologies

- Cross-modal alignment and reasoning between physiological signals (EEG, ECG, EMG) and multimedia (video/audio/text)
- Neuro-signal foundation models and large multimodal models (LMMs) for physiological data
- Self-supervised and representation learning for multi-channel neurophysiological signals
- Robust learning under noise, artifacts, missing modalities, and domain shifts

#### Applications & Systems

- Clinical and healthcare neuro-multimedia applications (e.g., epilepsy detection, mental health, sleep analysis)
- Emotion, attention, and cognitive state modeling via joint internal-external sensing
- Human-centered AI, affective computing, and neuro-aware multimedia understanding
- Real-time processing and edge computing for wearable neuro-multimedia systems

#### Data, Evaluation & Ethics

- Dataset construction, open-source benchmarks, and evaluation protocols for neuro-multimedia
- Trustworthy AI: Explainability, bias mitigation, and ethics in physiological data processing
- Privacy-preserving machine learning and federated learning for sensitive neuro-signals

---

## Schedule

### 2026

- **Apr 20, 2026**: Data, baseline paper and baseline code available.
- **Jun 20, 2026**: Result submission starts.
- **Jul 1, 2026**: Result submission deadline.
- **Jul 23, 2026**: Paper submission deadline.
- **Aug 5, 2026**: Paper acceptance notification.
- **Aug 19, 2026**: Camera-ready deadline.

### 2025

- **Archive**: Preparatory work and proposal drafting period.

---

## Speakers

Invited speakers will be announced. (Section currently hidden on the web page)

---

## Organizing Committee

### Organizers

- Fei Ma — Guangdong Laboratory
- Zitong Yu — Great Bay University
- Larbi Boubchir — University of Paris 8
- Zheng Lian — Tongji University
- Philippe Fournier-Viger — Shenzhen University
- Hongbo Xu — Guangdong Laboratory
- Minghui Li — Guangdong Laboratory
- Karim Jerbi — University of Montreal
- Laizhong Cui — Shenzhen University
- Qi Tian — Guangdong Laboratory & Huawei

### Challenge and Data Chairs

- Zebang Cheng — Shenzhen University & Guangdong Laboratory
- Haibo He — NetEase Media Technology (Beijing)
- Qiang Lu — Peking Union Medical College Hospital
- Nan Lin — Peking Union Medical College Hospital
- Lian Li — NetEase Media Technology (Beijing)
- Peng Hu — NetEase Media Technology (Beijing)
- Zi Liang — NetEase Media Technology (Beijing)

---

## Contact

Official contact for workshop and challenge inquiries.

- **Official Contact**: contact@neuromm.org

### Specific Inquiries

- **Workshop-related collaborations and academic inquiries**: Fei Ma (Workshop Lead), mafei@gml.ac.cn
- **Challenge-related collaborations, participation, and benchmark inquiries**: Zebang Cheng (Challenge Lead), zebang.cheng@gmail.com

---

© 2026 NeuroMM Workshop and Grand Challenge
