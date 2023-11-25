graph TD

subgraph NPS
    NPS(NPS)
    purpose_NPS[Purpose: 고객 만족도 및 추천 의향 측정]
    measurement_NPS[측정 방법: 설문조사를 통한 0부터 10까지의 평가]
    steps_NPS[진행 절차]
    subgraph "NPS 진행 절차"
        A(설문조사 수행)
        B(고객 의견 수집)
        C(NPS 점수 계산)
        D(결과 분석 및 개선)
    end
end

subgraph "바이럴 마케팅"
    Viral(Viral Marketing)
    purpose_Viral[Purpose: 콘텐츠 전파를 통한 홍보]
    measurement_Viral[측정 방법: 콘텐츠의 자연스러운 전파 및 공유]
    steps_Viral[진행 절차]
    subgraph "바이럴 마케팅 진행 절차"
        E(매력적인 콘텐츠 생성)
        F(콘텐츠 공유 유도)
        G(사용자 간의 전파 확대)
        H(결과 분석 및 측정)
    end
end

subgraph "레퍼럴 마케팅"
    Referral(Referral Marketing)
    purpose_Referral[Purpose: 기존 고객을 통한 신규 고객 확보]
    measurement_Referral[측정 방법: 추천을 통한 새로운 고객 확보 및 보상]
    steps_Referral[진행 절차]
    subgraph "레퍼럴 마케팅 진행 절차"
        I(프로그램 설계)
        J(고객 모바일 또는 온라인 플랫폼 구축)
        K(보상 제공 및 추천 활성화)
        L(새로운 고객 확보 및 보상)
        M(결과 분석 및 개선)
    end
end

subgraph "입소문 순환 시간"
    WordOfMouth(입소문 순환 시간)
    purpose_WordOfMouth[Purpose: 긍정적인 소문 확산 속도 측정]
    measurement_WordOfMouth[측정 방법: 소셜 미디어 및 커뮤니케이션 채널에서의 정보 전파 속도]
    steps_WordOfMouth[진행 절차]
    subgraph "입소문 순환 시간 진행 절차"
        N(긍정적인 소문 생성)
        O(소문의 전파 및 확산)
        P(커뮤니케이션 채널에서의 전파 속도 측정)
        Q(결과 분석 및 개선)
    end
end

NPS -->|평가 및 의견| purpose_NPS
Viral -->|콘텐츠 공유| purpose_Viral
Referral -->|추천 및 보상| purpose_Referral
WordOfMouth -->|소문 전파 속도| purpose_WordOfMouth
