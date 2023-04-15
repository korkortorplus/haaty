# haaty
haaty หาตี้ ระบบสารสนเทศและการสื่อสารระหว่างอาสาฯ 😚 

> vote66 นี้เราไปตั้งป้อมที่หน่วยเลือกตั้งใกล้บ้านกัน


## The Front Problems
Vote 62 เรามีเวลาให้เพียง 2 วัน ในการหาอาสาฯ แต่หน่วยเลือกตั้งมีมากกว่า 90,000 หน่วย เราได้อาสาฯสุทธิ์แค่ 1000-2000 คน เพราะเรารอให้กกต.ประกาศเขต-หน่วยเลือกตั้งก่อน(ประเด็น 1)


![snapshot of vote62.com/volunteer](https://raw.githubusercontent.com/korkortorplus/.github/main/profile/2023-04-12-20-16-36.png)[snapshot 12 Apr 2566 of [vote62.com/volunteer](https://www.vote62.com/volunteer/)]

จริงๆ เราขาดการสื่อสาร ขาดเครื่องมือบริหารจัดการ อาสาฯทำงานแบบปัจเจกฯ ต่างคนต่างทำ

1. งงไม่รู้ว่าตัวเองอยู่หน่วยเลือกตั้งไหน กรอกข้อมูลไม่ถูก (เขตที่เท่าไหร่ หน่วยเลือกตั้งเท่าไร)
2. วันจริงมีรถ แต่งงไม่รู้ว่าไปหน่วยไหนต่อดี
3. ไม่รู้ว่ามีอาสาฯอื่นไหม ทำงานเดียวกัน ทำงานในหน่วยเดียวกันซ้ำซ้อนเกินจำเป็น
4. วันจริงมีรถ ไม่รู้ว่าหน่วยนี้นับเสร็จไปนานแล้ว ก็ไปใหม่


## ข้อเท็จจริง
ปัจจุบันไม่มีการเผยแพร่ข้อมูลเกี่ยวกับตำแหน่งหน่วยเลือกตั้ง เราอาจใช้การประมาณด้วยการเอาข้อมูลตำแหน่งหมู่บ้านในประเทศไทยมาแทนไปก่อน (Boostrapping)


## ข้อเสนอการแก้ปัญหา Proposed Solution
จัดทำระบบอาสาสมัครที่สามารถจองหน่วยเลือกตั้งเพื่อไปนับคะแนนได้ โดยอ้างอิงจาก GPS location ทำการเก็บด้วยความละเอียดหลายตารางกิโลเมตรเพื่อความเป็นส่วนตัวของผู้ใช้

## ขั้นตอนการใช้งาน
1. สมัครด้วย IG, Facebook, LINE, Twitter
2. ให้สิทธิ์ในการเข้าถึงตำแหน่งของผู้ใช้ 
3. แสดงหมู่บ้านใกล้ๆ และจองหมู่บ้านที่ต้องการได้ พร้อมบอกความหนาแน่น
4. ก่อนหรือวันจริง ลงข้อมูล Location หน่วยเลือกตั้งใกล้บ้าน [จบที่ตรงนี้ก็ได้ ขอบคุณมากๆแล้ว]
6. [แนะนำ] ผูกบัญชี discord เข้าห้องแชทไปพูดคุยกับอาสาฯในตำบลเดียวกัน
5. วันจริงอัพเดทสถานะ "เปิดหีบแล้ว", "เริ่มนับแล้ว", "เสร็จแล้ว"
6. [แนะนำ] ถ่ายรูปเซลฟี่กับเพื่อนร่วมอุดมการณ์ #กูก็นับ #กกตพลัส
7. ระหว่างนี้ ถ่ายรูปเก็บข้อมูล ตามระบบ Vote 62 ที่เคยมี
8. [ถ้าได้]ขับรถไปหน่วยเลือกตั้งที่ยังนับไม่เสร็จ โดยมีระบบช่วยแจ้งเตือน รายงานสถานการณ์ปัจจุบัน

## ผลลัพธ์ที่คาดหวัง
1. สามารถระบุ และนำไปสู่ขอความช่วยเหลือในพื้นที่ที่ยังไม่มีอาสาฯได้ (sharable) 
    1. เพิ่มจำนวนอาสาฯในพื้นที่ที่ยังไม่มีอาสาฯ
2. อาสาฯสามารถทำงานเป็นทีม บนข้อมูลปัจจุบัน ที่ระบบสามารถสนับสนุนได้
3. สร้างฐานข้อมูลตำแหน่งหน่วยเลือกตั้ง ที่สามารถนำไปใช้ในการเลือกตั้งในอนาคตได้
4. อาสาฯพบเจอเพื่อร่วมอุดมการณ์ใกล้บ้าน


# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
