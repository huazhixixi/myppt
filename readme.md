# 设置

1. 确保width:height 为16:9 分辨率
2. section 添加h-100
3. container-fluid 添加height:90%; 因为nav占用了10%的高度
4. row 添加h-100，如果需要某些列居中可以align-self-center,如果所有列都需要居中，可以在row添加align-items-center 
5. 添加column，column会被自动限制宽度在row中