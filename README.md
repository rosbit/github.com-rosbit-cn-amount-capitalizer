## 数字金额转中文大写金额

 - 可以转换到`万万亿`级别

### 使用方法
 - 见测试程序`a_test.go`
   ```bash
   $ go test
   435235324532.00 => 肆仟叁佰伍拾贰亿叁仟伍佰叁拾贰万肆仟伍佰叁拾贰圆整
   100.02 => 壹佰圆零贰分
   10100.02 => 壹万零壹佰圆零贰分
   340210100.02 => 叁亿肆仟零贰拾壹万零壹佰圆零贰分
   3400000000.02 => 叁拾肆亿圆零贰分
   4352352343400000000.00 => 肆佰叁拾伍万万亿贰仟叁佰伍拾贰万亿叁仟肆佰叁拾肆亿圆整
   0.00 => 零圆
   0.12 => 壹角贰分
   9999.00 => 玖仟玖佰玖拾玖圆整
   19800.00 => 壹万玖仟捌佰圆整
   2980.00 => 贰仟玖佰捌拾圆整
   500200.00 => 伍拾万零贰佰圆整
   103.00 => 壹佰零叁圆整
   PASS
   ok  	github.com/rosbit/cn-amount-capitalizer	0.240s
   ```
