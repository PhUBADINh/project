<template>
    <div class="flex justify-center">
        <div class="flex justify-center bg-[#E1F5FE] w-full max-w-[800px] h-auto m-[10px]  relative rounded-2xl p-6 shadow-lg">
        <div class=" mb-4 text-center">
            <span class="font-bold text-xl">ดร.นพ. สาโรช สุวรรณสุทธิ</span>
        </div>
        
        <div class="flex flex-wrap gap-4 justify-center md:justify-start">
            <img src="/src/img/profile-user.png"
                alt="Doctor Image"
                class="w-full max-w-[15rem] h-auto object-cover object-center rounded-lg">
            
            <div class="flex flex-col flex-grow">
            <div class="flex items-center mb-2">
                <span class="font-bold mr-2">รพ.ที่สังกัด :</span>
                <span>โรงพยาบาลสมิติเวช สุขุมวิท</span>
            </div>
            <div class="flex items-center mb-2">
                <span class="font-bold mr-2">คะแนนรีวิว :</span>
                <span>4.95 (267 รีวิว)</span>
            </div>
            <div class="flex items-center mb-2">
                <span class="font-bold mr-2">ประเภทการรักษา :</span>
                <span>Laser, Ultherapy, ปรับรูปหน้า, ผม-หนังศีรษะ...</span>
            </div>
            <div class="flex flex-col mt-4">
                <span class="font-bold text-lg">ความชำนาญ</span>
                <ul class="list-disc list-inside">
                <li>โรคเส้นผม และการผ่าตัดปลูกถ่ายเส้นผม</li>
                <!-- Add more specialties here if needed -->
                </ul>
            </div>
    
            <!-- คุณวุฒิทางการศึกษา Section Moved Here -->
            <div class="flex flex-col mt-6">
                <span class="font-bold text-lg mb-2">คุณวุฒิทางการศึกษา</span>
                <ul class="list-disc list-inside">
                <li>American board of hair restoration surgery, 2017</li>
                <li>วุฒิบัตรผู้เชี่ยวชาญสาขาตจวิทยา แพทยสภา ปี พ.ศ.2555</li>
                <li>Doctor of Philosophy in Medical Science (Gene Therapy), Osaka University, 2007</li>
                <!-- Add more qualifications here if needed -->
                </ul>
            </div>
    
            <div class="flex flex-col mt-6">
                <span class="font-bold text-lg mb-2">ค่าบริการ</span>
                <ul class="list-disc list-inside">
                <li>แชท: ฿400 (สุงสุด 15 นาทีต่อครั้ง)</li>
                <li>วิดิโอคอล: ฿500 (สุงสุด 15 นาทีต่อครั้ง)</li>
                
                <!-- Add more qualifications here if needed -->
                </ul>
            </div>
            </div>
        </div>
        </div>
    </div>

  </template>
  
  <style>
    /* Utility classes for spacing, text formatting, and layout */
    .flex {
      display: flex;
    }
    .flex-col {
      display: flex;
      flex-direction: column;
    }
    .flex-wrap {
      flex-wrap: wrap;
    }
    .flex-grow {
      flex-grow: 1;
    }
    .items-center {
      align-items: center;
    }
    .justify-center {
      justify-content: center;
    }
    .justify-start {
      justify-content: flex-start;
    }
    .mr-2 {
      margin-right: 0.5rem;
    }
    .mb-2 {
      margin-bottom: 0.5rem;
    }
    .mb-4 {
      margin-bottom: 1rem;
    }
    .mt-4 {
      margin-top: 1rem;
    }
    .mt-6 {
      margin-top: 1.5rem;
    }
    .list-disc {
      list-style-type: disc;
    }
    .list-inside {
      list-style-position: inside;
    }
    .bg-white {
      background-color: #fff;
    }
    .p-6 {
      padding: 1.5rem;
    }
    .rounded-lg {
      border-radius: 0.5rem;
    }
    .rounded-2xl {
      border-radius: 1rem;
    }
    .shadow-lg {
      box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
    }
    /* Responsive Design */
    @media (max-width: 768px) {
      .flex-wrap {
        flex-direction: column;
      }
      .justify-center {
        justify-content: center;
      }
    }
  </style>
  