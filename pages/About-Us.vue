<template>
  <v-row>
    <v-col class="display-destop" sm="6">
      <v-img src="/us.png"></v-img>
    </v-col>
    <v-col sm="6">
      <v-card elevation="0">
        <v-card-title>About Us (เกี่ยวกับเรา)</v-card-title>
        <v-card-text style="text-align: justify">
          <h3>
            เว็บเราเป็นชุมชนออนไลน์ ที่มีความตั้งใจในการเป็นตัวกลางเพื่อถ่ายทอดผลงานของผู้แปลท่านต่างๆ โดยผลงานหลักๆนั้นเป็นประกอบไปด้วย
            • ผลงานแปล Manga (ญี่ปุ่น), Manhwa (เกาหลี), จีนและ Comic (ตะวันตก) , Doujin (R18+)
            • ผลงานวาด Doujin (ศัพท์ญี่ปุ่น) แต่ผลงานการ์ตูนออริจินัลฝีมือคนไทย
            • ผลงานนิยายทั้งการแปลจากภาษาต่างๆรวมทั้งการประพันธ์โดยเหล่าสมาชิกครับ
            ซึ่งเป็นผลผลิตจากความมานะ อุตสาหะของเหล่าสมาชิกโดยเว็บไซต์เรามีระบบหลังบ้าน เพื่อจัดการผลงานต่างๆ และเปิดรับผลงานไม่ละเมิดลิขสิทธิ์ในประเทศไทย หากว่าผลงานดังกล่าวมีการได้รับลิขสิทธิ์จากประเทศไทย ทางทีมงานก็จะเอาออกผลงานนั้นออกแล้วโปรโมทผลงานนั้นต่อ Social Network เพื่อให้ผู้สนใจสามารถสนับสนุนต่อผู้ได้รับลิขสิทธิ์อย่างถูกต้องง
          </h3>
        </v-card-text>
        <v-card-title>Contact Us (ติดต่อเรา)</v-card-title>
        <v-card-text style="text-align: justify">
          <h3>ติดต่อแอดมินผ่านช่องทาง Facebook ,หรือที่อีเมลล์ seven2channel@gmail.com</h3>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  head() {
    return {
      title: `เกี่ยวกับเรา`,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'เว็บเราเป็นชุมชนออนไลน์ ที่มีความตั้งใจในการเป็นตัวกลางเพื่อถ่ายทอดผลงานของผู้แปลท่านต่างๆ โดยผลงานหลักๆนั้นเป็นประกอบไปด้วย • ผลงานแปล Manga (ญี่ปุ่น), Manhwa (เกาหลี), จีนและ Comic (ตะวันตก) , Doujin (R18+) • ผลงานวาด Doujin (ศัพท์ญี่ปุ่น) แต่ผลงานการ์ตูนออริจินัลฝีมือคนไทย • ผลงานนิยายทั้งการแปลจากภาษาต่างๆรวมทั้งการประพันธ์โดยเหล่าสมาชิกครับ ซึ่งเป็นผลผลิตจากความมานะ อุตสาหะของเหล่าสมาชิกโดยเว็บไซต์เรามีระบบหลังบ้าน เพื่อจัดการผลงานต่างๆ และเปิดรับผลงานไม่ละเมิดลิขสิทธิ์ในประเทศไทย หากว่าผลงานดังกล่าวมีการได้รับลิขสิทธิ์จากประเทศไทย ทางทีมงานก็จะเอาออกผลงานนั้นออกแล้วโปรโมทผลงานนั้นต่อ Social Networkเพื่อให้ผู้สนใจสามารถสนับสนุนต่อผู้ได้รับลิขสิทธิ์อย่างถูกต้อง'
        },
        {
          hid: 'twitter:title',
          name: 'twitter:title',
          content: `เกี่ยวกับเรา`
        },
        {
          hid: 'twitter:description',
          name: 'twitter:description',
          content:
            'เว็บเราเป็นชุมชนออนไลน์ ที่มีความตั้งใจในการเป็นตัวกลางเพื่อถ่ายทอดผลงานของผู้แปลท่านต่างๆ โดยผลงานหลักๆนั้นเป็นประกอบไปด้วย • ผลงานแปล Manga (ญี่ปุ่น), Manhwa (เกาหลี), จีนและ Comic (ตะวันตก) , Doujin (R18+) • ผลงานวาด Doujin (ศัพท์ญี่ปุ่น) แต่ผลงานการ์ตูนออริจินัลฝีมือคนไทย • ผลงานนิยายทั้งการแปลจากภาษาต่างๆรวมทั้งการประพันธ์โดยเหล่าสมาชิกครับ ซึ่งเป็นผลผลิตจากความมานะ อุตสาหะของเหล่าสมาชิกโดยเว็บไซต์เรามีระบบหลังบ้าน เพื่อจัดการผลงานต่างๆ และเปิดรับผลงานไม่ละเมิดลิขสิทธิ์ในประเทศไทย หากว่าผลงานดังกล่าวมีการได้รับลิขสิทธิ์จากประเทศไทย ทางทีมงานก็จะเอาออกผลงานนั้นออกแล้วโปรโมทผลงานนั้นต่อ Social Networkเพื่อให้ผู้สนใจสามารถสนับสนุนต่อผู้ได้รับลิขสิทธิ์อย่างถูกต้อง'
        },
        {
          hid: 'twitter:card',
          name: 'twitter:card',
          content: 'read cartoon'
        },
        { hid: 'twitter:site', name: 'twitter:site', content: '@7toons' },
        { hid: 'twitter:creator', name: 'twitter:creator', content: '@7toons' },
        {
          hid: 'twitter:image',
          name: 'twitter:image',
          content: `/icon.png`
        },
        {
          hid: 'og:title',
          name: 'og:title',
          content: `เกี่ยวกับเรา `
        },
        {
          hid: 'og:site_name',
          name: 'og:site_name',
          content: `เกี่ยวกับเรา `
        },
        {
          hid: 'og:description',
          name: 'og:description',
          content:
            'เว็บเราเป็นชุมชนออนไลน์ ที่มีความตั้งใจในการเป็นตัวกลางเพื่อถ่ายทอดผลงานของผู้แปลท่านต่างๆ โดยผลงานหลักๆนั้นเป็นประกอบไปด้วย • ผลงานแปล Manga (ญี่ปุ่น), Manhwa (เกาหลี), จีนและ Comic (ตะวันตก) , Doujin (R18+) • ผลงานวาด Doujin (ศัพท์ญี่ปุ่น) แต่ผลงานการ์ตูนออริจินัลฝีมือคนไทย • ผลงานนิยายทั้งการแปลจากภาษาต่างๆรวมทั้งการประพันธ์โดยเหล่าสมาชิกครับ ซึ่งเป็นผลผลิตจากความมานะ อุตสาหะของเหล่าสมาชิกโดยเว็บไซต์เรามีระบบหลังบ้าน เพื่อจัดการผลงานต่างๆ และเปิดรับผลงานไม่ละเมิดลิขสิทธิ์ในประเทศไทย หากว่าผลงานดังกล่าวมีการได้รับลิขสิทธิ์จากประเทศไทย ทางทีมงานก็จะเอาออกผลงานนั้นออกแล้วโปรโมทผลงานนั้นต่อ Social Networkเพื่อให้ผู้สนใจสามารถสนับสนุนต่อผู้ได้รับลิขสิทธิ์อย่างถูกต้อง'
        },
        {
          hid: 'og:image',
          property: 'og:image',
          content: `/icon.png`
        }
      ]
    }
  }
}
</script>

<style></style>
