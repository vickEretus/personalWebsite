<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Education</template>
    York College of Pennsylvania, York PA			                 Expected graduation: May 2024
    Bachelor of Science in Computer Science						

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skills</template>

    SQL, Python, Java, C/C++, C#, HTML/CSS, Microsoft Package, Oracle VM VirtualBox, 
    Linux (Ubuntu), Draw.io, Figma, GitHub, Visual Studio Family
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Related Experience</template>
CS Capstone I – RevMetrix, Backend Team                                                 	           August 2023 – Current
•	Architect the foundation for our new capstone project
•	Conduct database and ORM prototypes to identify project requirements
•	Produced system architecture diagrams for effective communication with Draw.io & Figma
•	Strategically planning the seamless integration of new teams for efficient collaboration
•	Contributed to project documentation through a HUGO website, ensuring accuracy and accessibility
Advanced Graphics 
•	Implemented a DirectX11 individual self-study project in using the DirectXTK library. 
Software Engineering and Design						      January 2023 - May 2023
•	Enhanced understanding of traditional web application development by successfully completing a Java web application using legacy code.	                      
Individual Project – Self moving Camera				                  January 2023 - May 2023
•	Developed a face-tracking system using an Arduino UNO, servos, and a USB camera.
•	Assembled wires to power the servos and the Arduino UNO
•	Enhanced user experience by designing and programming a Python GUI with a camera preview.

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Work Experience</template>

    Help Desk Technician, York College of Pennsylvania Library Technology Services                                 Feb 2022 - Current
•	Provided technical support to customers in person, over the phone, and online, resolving technology and library-related problems to ensure customer satisfaction
•	Collaborated with other Help Desk team members and technology specialists to resolve complex issues and provide effective solutions
•	Delivered prompt and courteous customer service, listening to customer concerns and offering appropriate solutions in a friendly and professional manner
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Leadership</template>

    Treasurer of IEEE								         August 2023 – Current
•	Collaborated with other executive board members to strategize and execute fundraising initiatives.
•	Generated innovative event ideas and organized their execution, enhancing IEEE chapter engagement and brand with successful events


  </WelcomeItem>
</template>
