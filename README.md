# Amazon Sponsored Ads — 캠페인 최적화 및 예산 배분

![Amazon Ads](https://img.shields.io/badge/Amazon_Ads-FF9900?style=for-the-badge&logo=amazon&logoColor=white)
![Performance Marketing](https://img.shields.io/badge/Performance_Marketing-232F3E?style=for-the-badge)
![Campaign Optimization](https://img.shields.io/badge/Campaign_Optimization-146EB4?style=for-the-badge)

Amazon Sponsored Ads를 활용해 **Thermos 32oz 보온·보냉 물병의 검색 키워드 및 경쟁사 상품 페이지 광고를 직접 운영하고, 실제 캠페인 성과에 따라 예산과 입찰 전략을 조정한 퍼포먼스 마케팅 프로젝트**입니다.

초기에는 Keyword Targeting과 경쟁사 PDP(Product Detail Page) Targeting에 동일한 예산을 배분했습니다. 이후 실제 주문 데이터를 확인하면서 Keyword Campaign의 예산 비중을 단계적으로 확대했고, 캠페인 후반에는 ROAS까지 입찰 판단 기준에 포함했습니다.

최종적으로 CTR 목표는 달성했지만 CVR과 매출 목표는 달성하지 못했습니다. 따라서 결과를 성공으로 포장하기보다 **어떤 전략이 작동했고, 어디에서 전환이 막혔는지, 다음 캠페인에서는 무엇을 검증해야 하는지**까지 정리했습니다.

> **팀 프로젝트 — 5인 공동 수행**
>
> 팀원별로 업무를 고정 분담하기보다 제품 및 경쟁사 조사, 타기팅 설계, 캠페인 운영, 주차별 성과 분석, 예산·입찰 조정, 최종 개선안 도출까지 전 과정에 함께 참여했습니다.

---

## 1. 프로젝트 요약

| 항목 | 내용 |
|---|---|
| **문제** | 제한된 광고 예산을 Keyword와 경쟁사 PDP 중 어디에 배분해야 제품 노출과 매출을 효율적으로 확보할 수 있는가 |
| **제품** | Thermos ICON Series Stainless Steel Water Bottle — 32oz, Granite |
| **광고 채널** | Amazon Sponsored Ads |
| **초기 목표** | Product Visibility 및 Sales 확대 |
| **KPI** | CTR ≥ 0.5%, CVR ≥ 10%, Sales $1,350 |
| **초기 전략** | Keyword Targeting 50% / PDP Targeting 50% |
| **타기팅** | 경쟁 브랜드 Keyword + 경쟁사 Product Detail Page |
| **주요 경쟁사** | Ello, Hydro Flask, Yeti |
| **최종 결과** | 686,424 Impressions · 896 Clicks · 41 Conversions · CTR 0.7% · CVR 4.5% · Sales $1,087 |
| **핵심 의사결정** | Keyword Campaign이 PDP보다 더 많은 주문을 만들자 예산 비중을 단계적으로 확대 |
| **운영 기준** | Impressions, Clicks, Orders, CTR, CVR, Sales, ROAS |
| **결론** | Traffic 확보에는 성과가 있었지만 Conversion과 Sales는 목표 미달. 후속 과제는 유입 확대보다 구매 전환 개선 |

### 핵심 결과

- **Impressions:** 686,424
- **Clicks:** 896
- **Conversions:** 41
- **CTR:** **0.7%**
- **CVR:** **4.5%**
- **Sales:** **$1,087**
- 초기 Budget: **Keyword 50% / PDP 50%**
- 캠페인 중 Keyword의 주문 우위를 확인한 뒤 **75:25 → 85:15** 등으로 예산 조정
- 가장 많은 주문을 기록한 Keyword:
  - `Yeti water bottles` — 20 orders
  - `Hydro flask water bottles` — 6 orders
  - `Ello insulated water bottle` — 3 orders

> 특정 Match Type, 가격 또는 제품 속성이 성과 차이의 직접적인 원인이었다고 단정하지 않았습니다.  
> 본 프로젝트에서 관측된 결과와 검증이 필요한 가설을 구분해 해석했습니다.

---

## 2. 분석 질문

프로젝트는 세 가지 질문에서 시작했습니다.

### Q1. 어떤 경쟁사를 대상으로 광고할 것인가?

제품 특성과 가격대를 비교해 주요 경쟁 브랜드를 선정하고, 해당 브랜드를 검색하거나 상품을 보고 있는 고객에게 Thermos 제품을 노출하고자 했습니다.

### Q2. Keyword와 PDP 중 어디에 예산을 더 배분해야 하는가?

처음부터 한쪽이 더 효과적이라고 가정하지 않고 동일한 예산으로 시작한 뒤 실제:

- Impressions
- Clicks
- Orders
- Sales
- ROAS

를 비교해 예산을 이동시키기로 했습니다.

### Q3. 캠페인 목표를 실제로 달성했는가?

광고가 많이 노출되거나 클릭된 것만으로 성공이라고 판단하지 않고, 캠페인 시작 전에 설정한 CTR·CVR·Sales KPI와 최종 결과를 비교했습니다.

---

## 3. 캠페인 흐름

```mermaid
flowchart TD

    A["제품 분석<br/>Thermos 32oz"]

    B["경쟁사 분석<br/>Ello · Hydro Flask · Yeti"]

    C["타기팅 설계<br/>Keyword + Competitor PDP"]

    D["초기 Budget<br/>Keyword 50%<br/>PDP 50%"]

    E["성과 모니터링<br/>Impressions · Clicks · Orders"]

    F["1차 예산 조정<br/>Keyword 75%<br/>PDP 25%"]

    G["저성과 Target 정리<br/>Bid 유지 / 조정 / Pause"]

    H["2차 예산 조정<br/>Keyword 85%<br/>PDP 15%"]

    I["후반 최적화<br/>ROAS 기준 추가"]

    J["최종 KPI 평가<br/>CTR · CVR · Sales"]

    K["후속 실험 및 개선안"]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J
    J --> K
