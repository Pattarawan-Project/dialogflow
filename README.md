<?php
/**
 * Export to PHP Array plugin for PHPMyAdmin
 * @version 5.1.1
 */

/**
 * Database `chatbotdb`
 */

/* `chatbotdb`.`question` */
$question = array(
  array('ID_Q' => 'Q001','Question' => 'แนะนำสินค้า','Answer' => 'ค่ะ ตอนนี้สินค้าทางการเกษตรและประมงของเรามีกั้ง กุ้ง ปลา หมึก มะพร้าวและส้มโอค่ะ','ID_QT' => 'QT01','Username' => 'Milky'),
  array('ID_Q' => 'Q002','Question' => 'สินค้าทางการเกษตร','Answer' => 'ค่ะ ตอนนี้สินค้าทางการเกษตรมีมะพร้าวกับส้มโอค่ะ','ID_QT' => 'QT01','Username' => 'Milky'),
  array('ID_Q' => 'Q003','Question' => 'สินค้าทางการประมง','Answer' => 'ค่ะ ตอนนี้สินค้าทางการประมงมีกั้ง กุ้ง ปลา และหมึกค่ะ','ID_QT' => 'QT01','Username' => 'Milky')
);

/* `chatbotdb`.`questiontype` */
$questiontype = array(
  array('ID_QT' => 'QT01','Name_Type' => 'สอบถามเกี่ยวกับสินค้า','Username' => 'Butter'),
  array('ID_QT' => 'QT02','Name_Type' => 'สอบถามการจัดส่งและช่องทางการชำระเงิน','Username' => 'Butter')
);

/* `chatbotdb`.`score` */
$score = array(
);

/* `chatbotdb`.`user` */
$user = array(
  array('Username' => 'Butter','Password' => '12345','First_Name' => 'พัทรภรณ์','Last_Name' => 'ศิกลิ่นแก้ว','Email' => 'admin@PRP.ac.th','User_Type' => 'admin','Tel' => '123456789'),
  array('Username' => 'Mali','Password' => 'kj458','First_Name' => 'เดือนเพ็ญ','Last_Name' => 'แขไข','Email' => 'moon@school.ac.th','User_Type' => 'customer','Tel' => '654879521'),
  array('Username' => 'Milky','Password' => '9876l','First_Name' => 'มินตรา','Last_Name' => 'หอมจัง','Email' => 'admin2@PRP.ac.th','User_Type' => 'admin','Tel' => '648518787'),
  array('Username' => 'zjaja','Password' => 'suk000','First_Name' => 'คงกระพัน','Last_Name' => 'ชาตรี','Email' => 'lee@school.ac.th','User_Type' => 'customer','Tel' => '649751252')
);
