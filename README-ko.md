# 2xbin-Mirivoice-TTS
언어 : [English](/README.md) | [한국어](/README-ko.md)

---

녹음본 MV-KOR-AA-NORMAL-0-036

https://github.com/user-attachments/assets/3f238bef-a6a8-4a43-9f1f-e0b70025c633

동일한 문장의 빈빈 미리보이스 출력 오디오

**아직 제공되지 않음**

---

우타우 캐릭터 `빈빈`의 [미리보이스](https://github.com/EX3exp/MiriVoice/)용 코퍼스 녹음 데이터입니다.

이 데이터세트에서는 441000Hz, 16bit의 WAV 녹음형식으로 녹음된 [aihub 애니체 말뭉치](https://github.com/EX3exp/MiriVoiceSupport-CorpusManager/releases/tag/1.0.0) 녹음본이 포함되어 있습니다.

녹음된 스타일 리스트
- Normal : 0 ~ 250
- Bright : N/A
- Angry : N/A
- Sad : N/A

이 데이터세트의 모든 오디오는 Shure sm58을 사용해 녹음 되었으며, Izotope RX 10을 사용해 잡음 제거 처리가 되어있습니다.

사용된 잡음 제거 프로세스
- RX 배치 프로세서 사용
- Mouth De-Click (Sensitivity 10.0)
- Voice De-noise (Adaptive Mode, Music, Surgical, Threshold 5.2, Reduction 11.3)
- Resample (New Sampling Rate 44100)
- Mixing (Mix to Mono)

이 데이터세트는 전문 성우가 녹음하지 않았으며, 그렇기 때문에 여러 발음 문제가 있을 수 있습니다.

---

## 이용 규약

1. 본 데이터세트를 TTS 모델의 학습에 사용할 수 있습니다.
2. 본 데이터세트를 연구목적으로 사용할 수 있습니다.
3. 본 데이터세트를 사용하여 SVC 방법을 사용하여 고유한 데이터세트를 만들 수 있습니다.
   4-1. 이 경우에는 제작된 모델을 배포할 수 있지만, 변환된 데이터세트는 배포할 수 없습니다.
   4-2. 목소리 제공자의 명시적 허락이 없을 경우, 이 데이터세트를 활용해 데이터셋을 만들 수 없습니다.
4. 본 데이터세트를 **변조하지 않고**, 그대로 데이터세트로 사용해 캐릭터 `빈빈`과 동일한 목소리의 캐릭터를 만들어 배포할 수 없습니다.
5. 어떤 방법으로든 본 데이터세트를 사용한 경우, 해당 데이터를 사용했다는 표기를 남겨주세요.
     - 예시 : 이 모델은 `빈빈 미리보이스 TTS` 공개 데이터를 SVC로 변환해 제작되었습니다.
  
위에 사용범위를 벗어나는 모든 내용은 `CC BY-NC-SA 4.0`를 따릅니다.