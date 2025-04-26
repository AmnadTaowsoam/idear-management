**ชื่อไอเดีย & UVP**  
**BrewMuse AI: Personalized Pour-Over Plans**  
“สูตรกาแฟพิเศษเฉพาะคุณ ทุกเดือน พร้อมคู่มือวิดีโอ & ลิ้งค์ซื้อเมล็ดแนะนำ”

---

**คำอธิบายสั้น**  
Subscription service ใช้ GPT สร้างสูตร pour-over รายเดือน ปรับตามรสนิยม สร้างคู่มือวิดีโอสั้น 3–5 นาที พร้อมลิงก์ affiliate ให้ซื้อเมล็ดกาแฟคุณภาพสูง

---

**ภาพรวมธุรกิจ & Gap Analysis**  
- **Pain**: คนรักกาแฟเสียเวลาเสิร์ชสูตร-เรียนวิธีต้มด้วยตัวเอง  
- **Solution**: Auto-generate brew plan + video tutorial + shopping list  
- **Gap**: ไม่มีใครทำ “personalized coffee plan” เจาะลึก pour-over + affiliate

---

**Customer Personas & User Journeys**  
- **Coffee Aficionado (อายุ 25–45)**  
  1. ค้นหา “pour over guide”  
  2. สมัคร Free tier (1 สูตร sample)  
  3. ทดลองต้มตามสูตร + ดูวิดีโอ 3 นาที  
  4. อัปเกรด Premium  
- **Home Barista Starter (อายุ 20–35)**  
  1. รับคูปองทดลอง 7 วัน  
  2. ต้มตามแผน 4 สัปดาห์  
  3. ซื้อรายปี (ได้แถม workshop ออนไลน์)

---

**ฟีเจอร์ MVP & Tech Stack**  
- **MVP**  
  - Next.js form รับ taste profile + equipment  
  - GPT-4 API → generate recipe steps & brew ratios  
  - FFmpeg + TTS → video tutorial (3–5 นาที)  
  - Affiliate link builder (Shopify partners)  
  - Stripe billing + member dashboard  
- **Tech Stack**: Next.js, Node.js, PostgreSQL, Redis, AWS Lambda, Stripe, OpenAI API, FFmpeg

---

**Pricing Tiers & โมเดลรายได้**  
- **Free**: 1 recipe sample + PDF  
- **Basic ฿199/เดือน**: 2 recipes + video + emails  
- **Premium ฿399/เดือน**: 4 recipes + video + monthly live Q&A + affiliate coupon  
- **Annual ฿3,990/ปี**: ทุกฟีเจอร์ + workshop

---

**จุดเด่น**  
- สูตร tailor-made ตามรสนิยม  
- วิดีโอสั้น 3–5 นาที ดูตามได้เลย  
- รายได้เสริมจาก affiliate coffee beans

---

**จุดด้อย & ความเสี่ยง**  
- พึ่งพา GPT (อาจต้องแก้ไขเล็กน้อย)  
- คุณภาพวิดีโอ DIY  
- ความผันผวนราคากาแฟ affiliate

---

**Sample Marketing Copy & Tagline**  
> “BrewMuse AI — เปลี่ยนเมล็ดกาแฟธรรมดาให้เป็นประสบการณ์ pour-over พิเศษ ทุกเดือน”  

---

**Roadmap Phases & Timeline**  
1. **W1–4**:  
   - Build signup/form + GPT integration (80 ชม.)  
2. **W5–8**:  
   - Video pipeline + affiliate link builder (60 ชม.)  
3. **W9–12**:  
   - Stripe + dashboard + beta (50 ชม.)  
4. **W13–16**:  
   - Launch public + partnerships

---

**กลยุทธ์ตลาด, Partnership & Distribution**  
- Ads บน Instagram targeting coffee gear enthusiasts (CAC ~฿450)  
- Partnership: ร้านกาแฟ specialty roasters แจกโค้ดส่วนลด  
- Distribution: YouTube shorts สอนวิธีต้มบางส่วน

---

**User Feedback & Iteration Plan**  
- **Month 1**: NPS survey + feature poll  
- **Month 2**: A/B test video length (3 vs 5 นาที)  
- **Month 3**: เพิ่มฟีเจอร์ community brew logs

---

**Compliance & Legal Considerations**  
- ปฏิบัติตาม OpenAI Terms  
- Affiliate disclosures (“เราอาจได้ค่าคอมมิชชั่น”)  
- Privacy Policy & PDPA/GDPR compliance

---

**แนวทางสเกล & อัตโนมัติ**  
- Vercel + AWS Lambda auto-scale  
- CloudWatch cron อัปเดตสูตรตามเทรนด์กาแฟ  
- CDN (CloudFront) เก็บ video static

---

**Exit Strategy & Long-Term Vision**  
- ขยายเป็น marketplace ให้ micro-roasters ขายสูตร/แพลน  
- ขายกิจการให้ VC สาย F&B Tech ภายใน 3–5 ปี

---

**Unit Economics & Financial Forecast**  
- **ต้นทุนเริ่มต้น**:  
  - Dev: 190 ชม. × ฿800 = ฿152,000  
  - GPT API: ฿1,200/เดือน  
  - Video processing & hosting: ฿800/เดือน  
- **Revenue Projection**:  
  - M3: 100 Basic × ฿199 = ฿19,900  
  - M6: 150 Basic + 30 Premium = (150×199 + 30×399) = ฿29,850 + ฿11,970 = ฿41,820  
- **Breakeven**: ~130 Basic users (~5 เดือน)

---

**Success Metrics & OKRs**  
- **CAC** < ฿500/user  
- **LTV** ≥ ฿2,000  
- **Churn** < 5%/เดือน  
- **Q2 OKR**:  
  - O: Onboard 200 trial users  
  - KR1: 70 Premium conversions  
  - KR2: NPS ≥ 40

---

**Actionable First Milestone**  
- เปิด repository + Next.js form + GPT recipe call (Deadline: 7 วัน)

---

**Tone & Voice Guidelines**  
- Friendly-professional, เน้น passion ของ coffee lovers  
- ใช้ “คุณ” ให้ใกล้ชิด พร้อมตัวเลขชัดเจน

---

**Format Constraints**  
- ไม่เกิน 800 คำ  
- Markdown headings ตามหัวข้อ  
- มีตัวเลขประมาณการณ์ครบถ้วน  
