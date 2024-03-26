# Generic Components
This document lists downs and describes all the components that can be used to create a task on the Karya Platform.

### User Components

| Available on android | Available on Web Portal |
| --------------------- | ---------------------- |
| **UserAudioComponent** <br> bitwidth: EnumInputParam <br> sampling_rate: EnumInputParam <br> compress: BooleanInputParam? <br> min_recording_length: IntegerInputParam? <br> max_recording_length: IntegerInputParam? <br> force_replay: BooleanInputParam? <br> recording: FileOutputParam <br> duration: IntegerOutputParam <br> next: ReferenceInputParam | |
| **UserAudioMarkerComponent** <br> recording: FileInputParam <br> min: IntegerInputParam? <br> max: IntegerInputParam? <br> markers: IntegerArrayOutputParam <br> next: ReferenceInputParam | |
| **UserBooleanComponent** <br> question: StringInputParam <br> answer: BooleanOutputParam <br> next: ReferenceInputParam | |
| **UserFillInBlanksComponent** <br> question: StringInputParam <br> blanks: ArrayInputParam <br> answers: ArrayOutputParam <br> next: ReferenceInputParam | |
| **UserImageAnnotationComponent** <br> image: FileInputParam <br> annotations: ArrayInputParam? <br> min: IntegerInputParam? <br> max: IntegerInputParam? <br> enable_adjustment: BooleanInputParam? <br> annotated_image: FileOutputParam <br> next: ReferenceInputParam | |
| **UserImageComponent** <br> image: FileInputParam <br> next: ReferenceInputParam | |
| **UserMCQComponent** <br> question: StringInputParam <br> options: ArrayInputParam <br> answer: IntegerOutputParam <br> next: ReferenceInputParam | |
| **UserRateComponent** <br> question: StringInputParam <br> min: IntegerInputParam <br> max: IntegerInputParam <br> answer: IntegerOutputParam <br> next: ReferenceInputParam | |
| **UserTextComponent** <br> text: StringInputParam <br> next: ReferenceInputParam | |
| **UserTextSelectComponent** <br> text: StringInputParam <br> options: ArrayInputParam <br> answer: IntegerOutputParam <br> next: ReferenceInputParam | |
| **UserVideoComponent** <br> video: FileInputParam <br> next: ReferenceInputParam | |
| **UserWordCloudComponent** <br> words: ArrayInputParam <br> word_cloud: FileOutputParam <br> next: ReferenceInputParam | |

### Platform Components
| Available on android | Available on Web Portal |
| --------------------- | ---------------------- |
| **PlatformAudioComponent** <br> audio: FileInputParam <br> next: ReferenceInputParam | |
| **PlatformImageComponent** <br> image: FileInputParam <br> next: ReferenceInputParam | |
| **PlatformImageMaskComponent** <br> image: FileInputParam <br> mask: FileInputParam <br> next: ReferenceInputParam | |
| **PlatformTextComponent** <br> text: StringInputParam <br> next: ReferenceInputParam | |
| **PlatformVideoComponent** <br> video: FileInputParam <br> next: ReferenceInputParam | |

### Background Local Components
| Available on android | Available on Web Portal |
| --------------------- | ---------------------- |
| **ArrayFilterLocalComponent** <br> array: ArrayInputParam <br> condition: StringInputParam <br> filtered_array: ArrayOutputParam <br> next: ReferenceInputParam | |
| **CheckAudioClippingComponent** <br> recording: FileInputParam <br> clipping: BooleanOutputParam <br> next: ReferenceInputParam | |
| **CheckInRangeComponent** <br> value: IntegerInputParam <br> min: IntegerInputParam <br> max: IntegerInputParam <br> in_range: BooleanOutputParam <br> next: ReferenceInputParam | |
| **CopyComponent** <br> source: AnyInputParam <br> destination: AnyOutputParam <br> next: ReferenceInputParam | |
| **FetchDistrictNamesComponent** <br> state: StringInputParam <br> districts: ArrayOutputParam <br> next: ReferenceInputParam | |
| **NullCheckLocalComponent** <br> target: AnyInputParam <br> is_null: BooleanOutputParam <br> next: ReferenceInputParam | |
| **SegmentAudioComponent** <br> recording: FileInputParam <br> threshold: FloatInputParam? <br> segments: ArrayOutputParam <br> next: ReferenceInputParam | |
| **VaaniPriorityBgComponent** <br> priority_options: ArrayInputParam <br> priority: IntegerOutputParam <br> next: ReferenceInputParam | |

### Background API Components
| Available on android | Available on Web Portal |
| --------------------- | ---------------------- |
| **UpdateAvatarBackgroundComponent** <br> next: ReferenceInputParam | |
