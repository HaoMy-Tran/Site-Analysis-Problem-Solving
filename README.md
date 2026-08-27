# Site Analysis's problem solving at Brewia: A Design thinking approach
(updating...)<br> 

<i>--scroll down for Vietnamese version--</i>

### 1. Setting the Context
Brewia is a prominent coffee chain in Vietnam aiming to expand its footprint and dominate the highly competitive F&B landscape. To execute this growth strategy, the **Expansion** department serves as the backbone, handling all planning and execution for New Store Openings (NSO).

Historically, expansion tasks were handled within a single unified team. However, over the past few years, the department split into two independent units to ensure maximum objectivity:
* **Site Finding:** Focuses on sourcing and negotiating potential locations.
* **Site Analysis:** Focuses on independently evaluating and analyzing the financial and commercial viability of those sites.

This separation was essential. In practice, Site Finders tend to overvalue prospective sites to push deals through—driven by commission incentives per NSO and potential commissions from landlords. Separating these roles allows Site Analysis to maintain an objective perspective and protect the company’s return on investment.

As a newly formed team, **Site Analysis** consists of a young, dynamic team of Freshers and Juniors. They are quick learners, highly adaptable, and proactive when facing complex challenges.

### 2. Problems Arise
When I joined the Site Analysis team as a location analyst, I immediately noticed a massive challenge ahead: **handling a heavy workload to meet Brewia's ambitious NSO targets for the upcoming year.**

Through conversations with the Team Leader and observing daily operations, I identified critical bottlenecks slowing down the team's efficiency:
* **Lengthy Presentations:** Site evaluation presentations were dragging on from 30 minutes to well over an hour per location.
* **Weak Arguments:** Key arguments presented by analysts lacked solid logic and structure.
* **Low Decision-Making Efficiency:** Leaders struggled to make solid, conclusive decisions after presentation sessions.
* **Rework and Data Waste:** Analysts frequently had to collect additional data and re-do analyses post-meeting.

Faced with these challenges, rather than jumping straight into traditional problem-solving methodologies like *Hypothesis-driven* or *Issue-tree* frameworks, I decided to adopt **Design Thinking** as the core approach for two reasons:
1. **This is a Human-Centered Problem:** The root causes stem directly from the team members' perspectives, habits, and mindsets. The ultimate solutions will be used by people. Imposing a rigid, mechanical framework right away would feel overly prescriptive and ineffective.
2. **Limited Initial Context:** As a new joiner, I lacked deep domain experience to form well-grounded hypotheses or construct a comprehensive issue tree from day one. Relying strictly on traditional methods risked getting stuck at the initial step: defining the problem.

Understanding the nature of the challenge and the team's dynamics, I realized I couldn't start by enforcing new processes or tools right away. Instead, I approached the problem through the lens of Design Thinking: starting with human empathy and navigating through each phase to uncover the real bottlenecks.

### Phase 1: Empathize
The objective of this phase was to gain a deeper understanding of the problem from the POV (Point of View) of the analysts.

I actively observed several presentation sessions and engaged in candid follow-up conversations with team members. Key findings included:
* **Confusion and Uncertainty:** Analysts struggled to determine the right analytical framework for new locations, often believing that *"every site is unique, with no two locations being the same."*
* **Weak Reasoning:** Arguments lacked robust evidence and backing rationale.
* **Reliance on Intuition:** Lacking a structured framework, analysts resorted to *"freestyling"* their analyses based on personal gut feel, which rarely yielded strong outcomes.

### Phase 2: Define
Synthesizing these qualitative insights, I mapped out an **Empathy Map** for the analyst team:

* **Think & Feel:** Analysts were trying hard, but analytical work felt overwhelming. Long presentation meetings with the Team Leader felt like a "battlefield." They felt helpless when put on the spot without clear answers.
* **Pains:** Uncertainty over which framework to use; anxiety about handling tough counter-questions from the Team Leader.
* **Gains:** A desire to shorten presentation times, reduce meeting friction, and eliminate post-presentation re-work.

From the Empathy Map, I derived **3 key Design Imperatives**:
1. Reduce stress and tension during presentation sessions.
2. Help analysts build logical thinking skills and attention to detail.
3. Establish a solid, standardized Analysis Framework as a clear guide for analysts.

### Phase 3: Ideate
Brainstorming solutions aligned with each Design Imperative:

* **Addressing Imperative 1 (Reduce presentation tension):**
  * *Option 1:* Re-explain the analysis flow and process (Attempted previously by the Leader, but issues persisted).
  * *Option 2 (Proposed):* **Role Modeling by the Leader**. For complex cases, the Leader demonstrates live problem-solving, data usage, and logical conclusion building to provide practical, visual learning.
* **Addressing Imperative 2 (Strengthen logical thinking):**
  * Conduct periodic logic exercises.
  * Encourage relevant domain reading.
  * Leverage AI/Chatbots to stress-test and challenge analytical perspectives.
* **Addressing Imperative 3 (Establish a Solid Analysis Framework):**
  * This emerged as the **Most Powerful Imperative**—the core key to solving the root cause of the team's performance bottlenecks.

### 3. Imperative 3: The Need for a Solid Analysis Framework
<img width="1167" height="175" alt="image" src="https://github.com/user-attachments/assets/49e83e20-7371-4d7c-a29b-55e7f15357b1" />

To understand why the Analysts team frequently felt confused, I systematically deconstructed the core meaning of each metric within the legacy flow:

*   **Market:** Evaluates overall market attractiveness and macro-level opportunities. Market analysis primarily falls under the Strategy team's scope to determine target new store counts. The Site Analysis team focuses on two micro-levels: Area and Site.
*   **Area:** Concentrates on analyzing the customer source (both quality and volume) within a 500m - 1000m radius around the site. Key methods include calculating target customer classes, benchmarking competitors and nearby stores, and analyzing traffic generators (schools, office buildings, tourist spots) alongside surrounding business activities.  
    $$\rightarrow \text{Area measures the \textbf{maximum potential} of the trade zone.}$$
*   **Site:** Evaluates intrinsic site attributes (excluding demographic/customer factors), such as physical facilities, visibility, accessibility, and site grade within the area.  
    $$\rightarrow \text{Site measures the \textbf{catchment capability}—how effectively the site captures Area potential.}$$
*   **Forecasted Revenue:** Revenue projection built on analog Brewia stores with similar trade zones, store formats, and customer profiles. Analysts typically present this to Leaders to secure a preliminary **GO** or **REJECT** decision.
*   **Financial Feasibility:** Integrates the forecasted revenue into the *Box of Economics* to evaluate CAPEX against revenue generation capability, establishing a ceiling rent for landlord negotiations.

#### Key Logical Flaws in the Legacy Framework
Through hands-on experience, I identified three major gaps:
1.  **Absence of an Early Kill-Switch:** Sites with severe legal roadblocks or overly complex physical layouts were not filtered out early, wasting analysis bandwidth only to be REJECTED later in the process.
2.  **Unsubstantiated Revenue Adjustments:** Applying analog store performance felt arbitrary without structured adjustment weights for Area and Site variations between the target site and benchmark stores.
3.  **Conflating Site Quality with Investment Viability:** Physical facility risks belong to CAPEX in the financial viability phase; using them as an arbitrary reason to abort a site midway creates noise in decision-making.

> **Root Cause:** The legacy structure lacked a clear distinction between **Necessary Conditions** and **Sufficient Conditions**. Analysts couldn't grasp the underlying logical narrative, making it difficult to construct a bulletproof presentation.

### Phase 4: Prototype

Redesigning the Framework: Multi-Stage Adjustment & Logic Gating

To solve these issues at the root, I redesigned the workflow by integrating a **2-Stage Revenue Adjustment Mechanism** and **Logic-Gated Criteria**:

<img width="1140" height="250" alt="image" src="https://github.com/user-attachments/assets/5042dfed-4c57-497a-b443-5484a8c77e30" />

Logic-Gated Criteria:
<img width="1061" height="302" alt="image" src="https://github.com/user-attachments/assets/db50e596-bf1b-454b-91e2-e664ec5d8119" />

Deep Dive into Framework Components

#### 1. Necessary conditions

*   **Legal Check:** Validates landlord ownership/leasing rights, commercial zoning compliance, construction permits, and fire safety (PCCC) clearances.
*   **Area Evaluation:** Leverages a **Hypothesis-Driven Pyramid** to evaluate four core pillars: Demand, Traffic Generators, Supply/Competition, and Area Sustainability. <br><br>
<img width="1110" height="575" alt="image" src="https://github.com/user-attachments/assets/1a7fba9f-dd80-4c62-81a1-f562bf2ec240" />

#### 2. 1st Revenue Forecast (Adjusted by Area Difference)
*   Selects the most suitable Analog Stores.
*   Evaluates Area variance (Demand, Traffic Generators, Competition) between the target site and each analog store.
*   Applies variance weights to calculate the Stage 1 Baseline Revenue ($Rev_1$).

#### 3. Sufficient conditions
*   Quantitatively scores site attributes using a structured matrix covering **Visibility**, **Accessibility**, **Position**, and **Facility**. Also, leverages a **Hypothesis-Driven Pyramid** to evaluate: <br><br>
<img width="1147" height="611" alt="image" src="https://github.com/user-attachments/assets/f1bf8ba4-d29a-4b6f-9900-376e64a46673" />

#### 4. 2nd Revenue Forecast (Adjusted by Site Difference)
*   Applies variance scores based on **Visibility**, **Accessibility**, and **Facility** *(excluding Position)* to adjust $Rev_1$.
*   Finalizes the adjusted **Average Daily Sales (ADS)** projection.

#### 5. Financial Feasibility (Box of Economics)
*   Feeds the final ADS figure into the operational P&L model.
*   Evaluates metrics against initial CAPEX and OPEX to assess core financial metrics: **Sales/CAPEX, IRR, ROIC, and Payback Period**.
*   Calculates a precise threshold rent to guide direct contract negotiations with the landlord.

<i>Vietnamese </i>



### 1. Bối cảnh
Brewia là một trong những chuỗi cà phê hàng đầu tại Việt Nam với mục tiêu mở rộng quy mô và thống lĩnh thị trường F&B đầy cạnh tranh. Để hiện thực hóa chiến lược này, khối **Expansion** đóng vai trò xương sống trong việc lập kế hoạch và triển khai mở mới cửa hàng (NSO - New Store Opened).

Trong khối Expansion, nhiệm vụ trước đây được đảm nhận chung bởi một bộ phận. Tuy nhiên, vài năm trở lại đây, bộ phận này đã được tách bạch thành hai đội ngũ độc lập nhằm đảm bảo tính khách quan tối đa:
* **Site Finding:** Tìm kiếm và đàm phán các mặt bằng tiềm năng.
* **Site Analysis:** Đánh giá, phân tích độc lập hiệu quả kinh doanh của mặt bằng.

Sự tách biệt này là vô cùng cần thiết. Thực tế cho thấy, các Site Finder thường có xu hướng đánh giá mặt bằng “hồng hóa” hơn thực tế để dự án nhanh chóng được duyệt—xuất phát từ động lực hoa hồng NSO và hoa hồng từ chủ nhà. Việc tách rời giúp Site Analysis giữ vững góc nhìn khách quan, bảo vệ hiệu quả đầu tư cho doanh nghiệp.

Ra đời sau, **Site Analysis** sở hữu một đội ngũ trẻ trung (Freshers & Juniors). Họ là những cá nhân có tư duy nhạy bén, khả năng thích ứng cao và rất chủ động trước các bài toán khó.

### 2. Vấn đề hiện diện
Khi mới gia nhập team Site Analysis với vai trò phân tích mặt bằng, tôi nhận thấy team đang đứng trước một bài toán lớn: **Khối lượng công việc khổng lồ để đáp ứng target NSO rất cao cho năm tiếp theo.**

Qua trao đổi với Team Leader và quan sát thực tế vận hành, tôi nhận diện được những "điểm nghẽn" nghiêm trọng đang làm giảm hiệu suất của cả đội:
* **Thời gian thuyết trình kéo dài:** Mỗi buổi presentation đánh giá mặt bằng thường lê thê từ 30 phút đến hơn 1 tiếng.
* **Lập luận thiếu vững chắc:** Các luận điểm thiếu tính logic, chưa đủ sức thuyết phục.
* **Hiệu quả ra quyết định thấp:** Sau buổi thuyết trình, dàn Leaders vẫn không thể đưa ra quyết định cuối cùng (Solid Decision).
* **Lãng phí nguồn lực:** Phải liên tục quay lại thu thập thêm dữ liệu và làm lại bản phân tích nhiều lần.

Đứng trước bài toán này, thay vì áp dụng ngay các phương pháp giải quyết vấn đề truyền thống như *Hypothesis-driven* hay *Issue tree*, tôi quyết định chọn **Design Thinking** làm hướng tiếp cận chủ đạo vì hai lý do:
1. **Đây là bài toán Human-Centered:** Nguyên nhân gốc rễ xuất phát từ chính góc nhìn và hành vi của các teammates. Giải pháp tạo ra sẽ do chính họ vận hành. Nếu áp đặt một quy trình logic cứng nhắc hay máy móc ngay từ đầu, team sẽ khó tiếp nhận.
2. **Bối cảnh thông tin hạn chế:** Là một thành viên mới, tôi chưa có đủ dữ liệu ngành để lập tức đưa ra giả thuyết (Form Hypothesis) hay dựng một Issue Tree toàn diện. Nếu đi theo lối cũ, tôi rất dễ bị tắc nghẽn ngay ở bước xác định bài toán.

Hiểu rõ bản chất vấn đề và bối cảnh của team, tôi nhận ra mình không thể bắt đầu bằng việc áp đặt ngay một bộ quy trình hay công cụ mới. Thay vào đó, tôi tiếp cận bài toán theo đúng tinh thần của Design Thinking: bắt đầu từ con người và đi qua từng giai đoạn cụ thể để gỡ rối từng nút thắt.

### Phase 1: Empathize (Thấu cảm)
Mục tiêu của giai đoạn này là tìm hiểu sâu bản chất vấn đề dưới góc nhìn (POV) của các bạn Analysts. 

Tôi trực tiếp tham gia các buổi thuyết trình, quan sát cách các bạn làm việc và chủ động lắng nghe chia sẻ của team sau mỗi buổi họp. Những ghi nhận thực tế bao gồm:
* **Tâm lý hoang mang:** Các bạn bối rối không biết nên áp dụng hướng tiếp cận nào cho từng mặt bằng mới, vì cho rằng *"mỗi địa điểm có một tính chất riêng, không cái nào giống cái nào"*.
* **Thiếu cơ sở lập luận:** Không đưa ra được chứng cứ hoặc logic đủ mạnh để bảo vệ quan điểm.
* **Phân tích theo cảm tính:** Khi mất phương hướng, các bạn chọn cách *"freestyle"* bài phân tích theo góc nhìn cá nhân, dẫn đến kết quả thuyết minh không đạt yêu cầu.

### Phase 2: Define (Xác định vấn đề)
Từ những dữ liệu định tính thu thập được, tôi tổng hợp thành **Empathy Map** cho đội ngũ Analyst:

* **Think & Feel:** Các bạn đã nỗ lực nhưng cảm thấy việc phân tích quá vượt sức. Mỗi buổi thuyết trình kéo dài với Team Leader không khác gì một "cuộc chiến". Cảm giác bất lực xuất hiện mỗi khi bị chất vấn mà không thể đưa ra câu trả lời thỏa đáng.
* **Pains:** Hoang mang vì không biết chọn khung phân tích nào; bất an vì không biết trả lời các câu hỏi phản biện của Leader ra sao.
* **Gains:** Mong muốn rút ngắn thời gian presentation, giảm bớt áp lực trong phòng họp và không phải sửa đổi/bổ sung data nhiều lần sau đó.

Từ Empathy Map, tôi đúc kết ra **3 Design Imperatives (Yêu cầu thiết kế giải pháp)**:
1. Leader cần giảm bớt căng thẳng trong quá trình presentation.
2. Bản thân các bạn Analysts cần rèn luyện tư duy logic và sự chi tiết (detail-oriented).
3. Cần có một Framework phân tích chung chuẩn chỉnh để các analysts dựa vào.

### Phase 3: Ideate (Tạo ý tưởng)
Đối chiếu với 3 Design Imperatives, tôi cùng team đào sâu tìm giải pháp:

* **Xử lý Imperative 1 (Giảm căng thẳng do bị hỏi dồn):** 
  * *Ý tưởng 1:* Giải thích lại chi tiết quy trình phân tích (Tuy nhiên, Leader đã làm nhiều lần nhưng vấn đề vẫn lặp lại).
  * *Ý tưởng 2 (Đề xuất):* **Leader làm mẫu (Role-modeling)**. Trong các case khó, Leader sẽ trực tiếp demo cách tiếp cận, cách xử lý data và cách đưa ra kết luận logic để team học hỏi trực quan.
* **Xử lý Imperative 2 (Rèn luyện tư duy logic):**
  * Thực hiện các bài test logic định kỳ.
  * Khuyến khích đọc thêm sách chuyên ngành.
  * Thấu hiểu và tận dụng AI/Chatbot hỗ trợ phản biện góc nhìn.
* **Xử lý Imperative 3 (Xây dựng Solid Analysis Framework):**
  * Đây chính là **Design Imperative quan trọng nhất (Most Powerful Imperative)**—chìa khóa cốt lõi giúp giải quyết triệt để gốc rễ của mọi vấn đề.


### 3. Imperative 3: Sự cần thiết cho một Khung phân tích hoàn chỉnh

### Bóc tách & Nhận diện Điểm yếu của Framework Cũ (Legacy Structure)

Quy trình phân tích cũ được vận hành như sau: <br><br>
<img width="1167" height="226" alt="image" src="https://github.com/user-attachments/assets/f4b6aa91-d49e-44d6-94d4-ea104493e06b" />
Để hiểu tại sao đội ngũ Analysts thường xuyên bối rối, tôi tiến hành bóc tách ý nghĩa bản chất của từng chỉ số trong quy trình cũ:

*   **Market (Thị trường):** Đo lường độ hấp dẫn tổng quan và cơ hội vĩ mô. Phân tích Market thuộc trách nhiệm chính của team Strategy để đề xuất số lượng store mở mới. Team Site Analysis chủ yếu tập trung vào 2 cấp độ vi mô hơn: Area và Site.
*   **Area (Khu vực):** Tập trung phân tích nguồn khách hàng (chất lượng & số lượng) trong bán kính 500m - 1000m xung quanh Site. Phương pháp bao gồm: tính toán tệp khách hàng mục tiêu, benchmarking đối thủ & các cửa hàng lân cận, phân tích điểm tạo lưu lượng (Traffic Generators: trường học, tòa nhà, điểm du lịch...) và hoạt động kinh doanh khu vực.  
    $$\rightarrow \text{Area đo lường \textbf{tiềm năng tối đa} của khu vực.}$$
*   **Site (Vị trí mặt bằng):** Đánh giá các yếu tố nội tại của chính mặt bằng (không bao gồm tệp khách hàng): cơ sở vật chất, độ nhận diện (Visibility), khả năng truy cập (Accessibility) và vị thế trong khu vực.  
    $$\rightarrow \text{Site đo lường \textbf{khả năng tận dụng/bắt sóng} tiềm năng từ Area.}$$
*   **Forecasted Revenue (Doanh thu dự phóng):** Dự báo doanh thu dựa trên các cửa hàng tương đồng (Analog Stores) về khoảng cách, mô hình cửa hàng, chân dung khách hàng... Từ đây, Leader sẽ đưa ra quyết định sơ bộ: **GO** hoặc **REJECT**.
*   **Financial Feasibility (Tính khả thi tài chính):** Tích hợp doanh thu dự báo vào mô hình tài chính (*Box of Economics*) để đối chiếu chi phí đầu tư với doanh thu kỳ vọng, từ đó xác định giá thuê trần hợp lý để đàm phán với chủ nhà.

#### Những Lỗ Hổng Logic Trong Framework Cũ
Thông qua thực tế vận hành, tôi nhận diện được 3 vấn đề lớn:
1.  **Thiếu cơ chế ngắt sớm (Early Kill-Switch):** Những mặt bằng bị vướng mắc pháp lý nghiêm trọng hoặc hình dáng quá phức tạp không được sàng lọc từ đầu, dẫn đến lãng phí thời gian phân tích các bước sau rồi mới REJECT.
2.  **Dự báo doanh thu thiếu cơ sở điều chỉnh:** Việc áp dụng doanh thu từ Analog Stores mang tính gượng ép khi không có trọng số điều chỉnh (*Adjustment Weight*) cho sự khác biệt về Area & Site giữa mặt bằng mới và cửa hàng đối chứng.
3.  **Lẫn lộn giữa chất lượng mặt bằng và bài toán đầu tư:** Rủi ro/yếu tố về cơ sở vật chất (*Facility*) thuộc về Site thực chất phản ánh vào Chi phí đầu tư (CAPEX) trong bài toán Tài chính, chứ không nên dùng làm lý do cảm tính để ngắt dự án ở giữa quy trình.

> **Gốc rễ vấn đề:** Structure cũ thiếu sự phân định chặt chẽ giữa **Điều kiện cần (Necessary Condition)** và **Điều kiện đủ (Sufficient Condition)**. Điều này khiến các Analysts không nắm được "sợi dây logic" cốt lõi, dẫn đến bài phân tích thiếu tính thuyết phục.

### Phase 4: Prototype (Tạo mẫu)
Tái Thiết Kế Framework: Multi-Stage Adjustment & Logic Gating

Để giải quyết triệt để vấn đề, tôi thiết kế lại luồng phân tích tích hợp **Cơ chế điều chỉnh doanh thu 2 bước (2-Stage Revenue Adjustment)** và **Bộ lọc điều kiện (Logic Gating)**: <br><br>
<img width="1161" height="251" alt="image" src="https://github.com/user-attachments/assets/1133c967-811e-4e8e-b910-4d5d2fd1414c" />

Ma Trận Logic Giữa Các Điều Kiện: <br><br>

<img width="1062" height="275" alt="image" src="https://github.com/user-attachments/assets/933dd067-1098-4bad-bb1d-27da17e4b60c" />

Chi Tiết Các Thành Phần Trong Framework Mới

#### 1. Điều kiện cần
*   **Legal Check:** Kiểm tra tính hợp pháp của chủ nhà, quy hoạch thương mại, điều kiện xin Giấy phép xây dựng (GPXD) và PCCC.
*   **Area Evaluation:** Ứng dụng **Hypothesis-driven Pyramid** để đánh giá toàn diện 4 trụ cột: Nhu cầu (Demand), Nguồn tạo lưu lượng (Traffic Generators), Cung ứng/Đối thủ (Supply), và Tính bền vững (Sustainability).<br><br>
<img width="1102" height="567" alt="image" src="https://github.com/user-attachments/assets/74feb8b1-0aa0-418d-8843-dc17076d5b48" />

#### 2. 1st Revenue Forecast (Adjusted by Area Difference)
*   Xác định các Analog Stores phù hợp.
*   So sánh sự khác biệt về Area (Nhu cầu, Traffic, Đối thủ) giữa mặt bằng mới và từng Analog Store.
*   Gán trọng số chênh lệch để tính toán ra Mức doanh thu dự báo giai đoạn 1 ($Rev_1$).

#### 3. Điều kiện đủ
*   Đánh giá định lượng mặt bằng dựa trên ma trận chấm điểm các chỉ số: **Visibility** (Nhận diện), **Accessibility** (Tiếp cận), **Position** (Vị trí) và **Facility** (Cơ sở vật chất).<br><br>
<img width="1140" height="597" alt="image" src="https://github.com/user-attachments/assets/59b97603-6361-436f-b066-43e2e8d57a0d" />

#### 4. 2nd Revenue Forecast (Adjusted by Site Difference)
*   Dựa trên điểm số của các yếu tố **Visibility**, **Accessibility**, và **Facility** *(loại trừ Position)* để gán trọng số chênh lệch cấp độ Site.
*   Điều chỉnh $Rev_1$ lần cuối để đưa ra Doanh thu trung bình ngày chính xác nhất (**ADS - Average Daily Sales**).

#### 5. Financial Feasibility (Box of Economics)
*   Đưa chỉ số ADS cuối cùng vào mô hình P&L vận hành.
*   Đối chiếu với Chi phí đầu tư ban đầu (CAPEX) và Chi phí vận hành (OPEX) để đánh giá các chỉ số hiệu quả đầu tư: **Sales/CAPEX, IRR, ROIC, Payback Period**.
*   Tính toán Mức giá thuê trần (*Rent Threshold*) chuẩn xác làm cơ sở đàm phán hợp đồng với chủ nhà.
