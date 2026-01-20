# Inmuebles24 Mexico Properties 데이터셋 샘플

<h2>1,236개 레코드로 구성된 샘플 데이터셋</h2>

<a href="https://brightdata.co.kr">
    <img src="https://github.com/luminati-io/Inmuebles24-Mexico-Properties-dataset-samples/blob/main/datasets-image.png" alt="Bright Data datasets" />
</a>

이 **Inmuebles24 Mexico Properties Dataset Sample**에는 **1,236개 레코드**가 포함되어 있으며 **Bright Data API**를 사용하여 추출되었습니다.

## Data Points

| Field Name | Description |
|------------|-------------|
| `url` | Inmuebles24에서 해당 부동산 매물 목록을 위한 고유 웹 주소입니다. |
| `Title` | 판매자가 제공한 부동산 매물의 기본 제목입니다. |
| `GeneratedTitle` | 유형 및 면적 등 부동산 세부 정보를 요약한 시스템 생성 제목입니다. |
| `Description` | 특징 및 위치를 포함한 부동산의 상세 설명입니다. |
| `Seller` | 부동산을 판매하는 개인 또는 조직의 이름/식별자입니다. |
| `Precio` | 지정된 통화로 표시된 부동산의 등록 가격입니다. |
| `Publicado_hace` | 매물이 등록된 이후 경과 시간을 일(day) 단위로 나타낸 값입니다. |
| `CreatedDate` | 플랫폼에서 해당 매물 목록이 생성된 날짜입니다. |
| `Visualizaciones` | 해당 매물 목록이 조회된 횟수입니다. |
| `Dimension_terreno` | 제곱미터 단위의 부동산 전체 토지 면적입니다. |
| `Dimension_propiedad` | 제곱미터 단위의 건물(연면적/전용 또는 커버된) 면적입니다. |
| `Estacionamiento` | 부동산에 포함된 주차 공간 수입니다. |
| `Banos` | 부동산 내 욕실 수입니다. |
| `Dormitorios` | 부동산 내 침실 수입니다. |
| `Antiguedad` | 일반적으로 연(year) 단위로 표시되는 부동산의 연식입니다. |
| `pictures` | 매물에 포함된 부동산 이미지에 대한 링크 또는 식별자입니다. |
| `videos` | 매물에 포함된 부동산 동영상에 대한 링크 또는 식별자입니다. |
| `Tipo_de_inmueble` | 아파트, 주택, 상업 공간 등 부동산 유형입니다. |
| `Tipo_de_operacion` | 판매 또는 임대 등 거래 유형입니다. |
| `Tipovendedor` | 소유주 또는 부동산 중개인 등 판매자 유형입니다. |
| `Phone1` | 부동산 문의를 위한 기본 연락처 전화번호입니다. |
| `whatsApp` | 즉시 메시지 문의를 위한 WhatsApp 연락처 번호입니다. |
| `Operacion` | 구매 또는 임대차 등 운영(거래) 유형을 지정합니다. |
| `Region` | 부동산이 위치한 더 넓은 지리적 지역입니다. |
| `Zona` | 부동산의 특정 구역 또는 동네입니다. |
| `Ciudad` | 부동산이 위치한 도시입니다. |
| `Provincia` | 부동산이 위치한 주/도(행정 구역)입니다. |
| `Direccion` | 부동산의 전체 주소입니다. |
| `Superdestacado` | 해당 매물이 플랫폼에서 추천/강조 표시되는지 여부를 나타냅니다. |
| `postingId` | 부동산 매물의 고유 식별자입니다. |
| `postingCode` | 부동산 매물을 나타내는 코드로, 종종 내부적으로 사용됩니다. |
| `publisher` | 매물이 광고되는 게시자 또는 플랫폼입니다. |
| `premier` | 매물이 프리미어 상태 또는 향상된 노출을 갖는지 여부를 나타냅니다. |
| `URL` | 해당 부동산 매물로 직접 연결되는 URL입니다. |
| `aviso_finalizado` | 매물이 최종 처리되었거나 종료되었는지 여부를 나타냅니다. |
| `currency` | 부동산 가격이 표시되는 통화입니다. |
| `latitude` | 부동산의 지리적 위도 좌표입니다. |
| `longitude` | 부동산의 지리적 경도 좌표입니다. |


## Use Cases

### 1. Real Estate Market Analysis
멕시코의 부동산 트렌드와 가격을 분석하여 부동산 전문가가 데이터 기반 투자 의사결정을 내리는 데 도움이 됩니다.

### 2. Competitive Benchmarking
여러 지역의 매물을 비교하여 경쟁 포지셔닝을 평가하고 부동산 마케팅 전략을 최적화합니다.

### 3. Urban Development Planning
지리 및 부동산 데이터를 활용하여 도시 계획가가 지속 가능하고 효율적인 도시 인프라를 설계하도록 지원합니다.



## File Formats

데이터셋은 여러 형식으로 제공됩니다:
- **CSV** (이 샘플에 포함됨)
- **JSON**
- **NDJSON**
- **JSON Lines**
- **Parquet**
- **Compressed (.gz)**

## Delivery Options

- **Email**
- **API Download**
- **Webhook**
- **Amazon S3**
- **Google Cloud Storage**
- **Microsoft Azure**
- **Snowflake**
- **SFTP**

## Update Frequency

데이터셋은 다양한 일정으로 업데이트될 수 있습니다:
- **Once** (1회성 전달)
- **Daily**
- **Weekly**
- **Monthly**
- **Quarterly**
- **Custom schedules**

## Data Enrichment

특정 요구사항에 따라 추가 데이터 포인트로 데이터셋을 강화할 수 있습니다. 맞춤형 enrichment 옵션은 문의해 주시기 바랍니다.

**[Get the full Inmuebles24 Mexico Properties dataset](https://brightdata.co.kr/products/datasets/real-estate)**

---

## Free Access for Researchers and NGOs

Bright Initiative는 환경 및 사회적 목적을 위해 활동하는 학술 연구자, NGO, NPO를 대상으로 **[Web Scraper APIs](https://brightdata.co.kr/products/web-scraper)** 및 **[ready-to-use datasets](https://brightdata.co.kr/products/datasets)**에 대한 무료 액세스를 제공합니다. 

[brightinitiative.com](https://brightinitiative.com)에서 무료 액세스를 신청하시기 바랍니다.