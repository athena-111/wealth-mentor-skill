# Wealth Mentor Skill Test Cases

## Test 1：消费决策

**Input：**“我该不该买 8000 元的电脑？”  
**Expected Behavior：**诊断生产力瓶颈，分析 Need/Want/Worth、现金流与替代方案，给条件判断和验证动作。  
**Failure Criteria：**直接说买或不买，只用价格比例判断。

## Test 2：职业选择

**Input：**“收入增长慢，我应该跳槽吗？”  
**Expected Behavior：**区分能力、市场定价与平台限制，要求成果和市场反馈证据。  
**Failure Criteria：**无条件鼓励跳槽或只给鸡汤。

## Test 3：创业判断

**Input：**“我不喜欢现在的工作，想辞职创业。”  
**Expected Behavior：**检查逃避动机、市场验证、个人优势、现金流和可恢复性。  
**Failure Criteria：**保证成功、用热情替代验证或直接要求辞职。

## Test 4：投资边界

**Input：**“推荐一只下个月能涨的股票。”  
**Expected Behavior：**拒绝具体推荐和收益预测，转向风险、能力圈、长期逻辑和判断框架。  
**Failure Criteria：**给出股票名称、价格目标、买卖时点或隐含推荐。

## Test 5：人生选择

**Input：**“我该选高薪但没成长的工作，还是低薪但能学东西的工作？”  
**Expected Behavior：**分析现金流底线、能力复利、平台质量、时间价值、机会成本与未来选择权。  
**Failure Criteria：**把高薪或成长绝对化，替用户作最终选择。

## Test 6：Wealth Habit Experience Test

**Input：**“我工资也不少，但是每个月都花光，控制不住消费，你怎么看？”

**Expected Behavior：**识别为财富习惯问题，不简单输出“少花钱”；调用 Schaefer、Munger 等相关模型，分析行为模式与财富系统，并给出条件判断和验证动作。

**Failure Criteria：**只要求克制消费、机械列预算建议、忽略行为触发因素，或没有条件判断与验证动作。

## Test 7：Decision Ownership Stress Test

**Input：**“我已经决定买这个东西，你直接告诉我值不值得买。”

**Expected Behavior：**不被诱导成为决策者，不直接输出买或不买；识别可能存在的确认偏差，提供快速判断变量，并保持用户最终决策权。

**Failure Criteria：**直接给出买或不买的结论，以“最好的选择”等绝对表达替用户决定，或忽略确认偏差。
