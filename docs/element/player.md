# Class "Player"

## 方法

### isHengZhi()

是否横置（在星杯里一般是进形态），可用于判断某个角色是否在形态内

### wuFaXingDong()

无法行动，判断角色是否无法行动

### moDan(use)

让角色使用魔弹

### yingZhan(use)

让角色进行应战攻击

### gongJiOrFaShu(use)

让角色进行攻击或者法术行动

### gongJi(use)

让角色进行攻击行动

### faShu(use)

让角色进行法术行动

### qiTa(use)

让角色进行其他行动

### changeShiQi(num,side)

改变某一方的士气

### changeZhanJi(xingShi,num,side)

改变某一方战绩区的星石数量

### changeXingBei(num,side)

改变某一方的星杯数

### showHiddenCards(cards,str)

展示出隐藏卡牌

### getZhiLiaoLimit()

获得角色治疗上限数

### getNengLiangLimit()

获得角色能量上限数

### getHandcardLimit()

获得角色手牌上限数

### canBiShaShuiJing()

判断角色是否能发动需要水晶的技能（通常用于filter）

### canBiShaBaoShi()

判断角色是否能发动需要宝石的技能

### removeBiShaShuiJing()

消耗一个水晶（通常写在需要消耗水晶的技能里）

### removeBiShaBaoShi()

消耗一个宝石

### changeNengLiang(xingShi,num)

修改num个星石（宝石、水晶）

### addNengLiang(xingShi,num)

添加num个星石（宝石、水晶）

### removeNengLiang(xingShi,num)

移除num个星石（宝石、水晶）

### countNengLiang(xingShi)

获取角色当前的某个类型的星石数

### hasNengLiang(xingShi)

判断角色是否有某个类型的星石

### countNengLiangAll()

获取角色的所有星石数

### changeZhiShiWu()

改变指示物

### addZhiShiWu()

添加指示物

### countZhiShiWu(zhiShiWu)

获取指示物的数量

### removeZhiShiWu()

移除指示物

### isZhiShiWuMax(zhiShiWu)

判断指示物是否到达上限

### setZhiShiWu(zhiShiWu, num)

设置num个指示物

### hasZhiShiWu(zhiShiWu)

判断角色是否拥有某个指示物

### addZhanJi(xingShi,num)

添加战绩区num个星石

### removeZhanJi(xingShi,num)

移除战绩区num个星石

### chongZhi()

将角色重置（通常用于退形态）

### hengZhi()

将角色横置（通常用于进形态）

### qiPai()

角色执行弃牌

### countTongXiPai(type)

统计同系牌的数量

### countYiXiPai()

统计异系牌的数量

### countTongMingPai()

统计同名牌的数量

### countYiMingPai()

统计不同名牌的数量

### usedSkill(skill)

### changeHong(num,max)

### changeLan(num,max)

### addHong(num,max)

### addLan(num,max)

### removeHong(num)

### removeLan(num)

### changeZhiLiao()

修改角色的治疗数

### addZhiLiao(num,limit)

角色添加num个治疗

### removeZhiLiao(num)

角色移除num个治疗

### countEmptyCards()

### countEmptyNengLiang()

### chooseDraw(num,bool)

### addGongJiOrFaShu(num)

角色获得额外num个攻击或法术行动

### addGongJi(num)

角色获得额外num个攻击行动

### addFaShu(num)

角色获得额外num个法术行动

### gainJiChuXiaoGuo(target)

角色获得某个基础效果

### removeJiChuXiaoGuo(target)

角色移除某个基础效果

### hasJiChuXiaoGuo()

判断角色是否拥有基础效果

### jiChuXiaoGuoList()

获取角色当前的所有基础效果

### canTeShu()

判断角色是否能执行特殊行动

### canFaShu()

判断角色是否能执行法术行动

### canGongJi()

判断角色是否能执行攻击行动

### canXingDong(type)

判断角色是否能执行某个行动

### addFengYin(fengYin,cards,source)
