<h2 id="简介">简介</h2>
<p>这是一个简单的CocosCreator虚拟摇杆demo</p>
<h2 id="种模式">3种模式</h2>
<ol>
<li>轮盘呼出模式 showMode<br>
[1] 固定位置 FIXED<br>
[2] 在限定区域呼出 FOLLOW</li>
<li>玩家移动模式 moveMode<br>
[1] 固定速度 FIXED<br>
[2] 随摇杆到轮盘中心距离变化 CHANGED</li>
<li>玩家越界模式 crossMode<br>
[1] 禁止越界 FORBID<br>
[2] 运行越界（即从另一侧出来）PERMIT</li>
</ol>
<h2 id="注意事项">注意事项</h2>
<ol>
<li><strong>rocker节点的size需要设置</strong>，不能为0，不然无法触发触摸事件</li>
<li>如果<strong>使用限制区域</strong>，则<strong>必须</strong>要让rocker节点成为限制区域节点的子节点，此操作涉及轮盘呼出的位置问题（坐标系错误，导致轮盘位置不对）</li>
<li>如果<strong>不使用限制区域</strong>，则不能使用轮盘呼出的跟随模式，否则会报错</li>
</ol>

