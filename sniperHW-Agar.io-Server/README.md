## Agar.io �������˿�ܽ��  
���������ļ�֮��Ĺ�ϵ��������߼�  
#### ��lua�ļ��ĺ���  
- ai.lua���趨�����Ϣ�����������AI���ƶ������λ�á�  
- ball.lua��������ball�е��������Ժͷ�����  
�����֮������  
1��function ball:fixBorder()��    
2��function ball:OnSelfBallOverLap(other)�����к����µ�manifold��  
- util.lua��һ����װ����Ϸ���������Ҫ�ĸ��ַ����Ĺ����ļ�������������ȥĤ�����¡��жϾ��롢�Ӽ��˳�������ת�������ʵȡ�  
- battle.lua������ս���������߼��������˻�ȡ���ID���½����䣬���뷿�䣬����ս��������ս����ս��������ͳ�Ʒ�����  
- battleuser.lua��ս����ҵ��߼���������֤�Ƿ�Ϊ��ʵ��ң���ֹ���ף�����Ҹ���ƶ�������λ�ã��ͷ��������ӣ����ѡ�  
- collision.lua���������Ƿ��������������������ײ��������ײ��������ײ���߼���    
��function collision:Update(o) --���ݶ���������¹���� ����⡣  
- collisionGrid.lua�������ײ��  
- config.lua����ս�������Ļ���Ԫ�ؽ��г�ʼ�������÷������ٶȣ��Ե����ء�  
�����֮������  
M.thornColorID = 22  
M.thornColor = {1,0,1,1}  
- genstar.lua���������ϵͳʱ�䣬���泤�����ҵ���ɫ��  
- minheap.lua���������������ҷ����ƶ����߼���������С��minheap������������  
- objtype.lua���趨M��Э�飬��star��ball��spore��thorn��  
- QuadTree.lua���Ĳ����㷨������Ҫ����  
- server.lua�������������˿ں���ͻ������ӵ��߼������ӳɹ�����߼���  
- star.lua�������߼������������£���������ͻ���֪ͨ������  
- testclient.lua���ͻ��˲����߼��������ڷ������˵������߼����������ơ�   
- user.lua�������û������˵��߼�����Ϣ�ַ����߼���  
�����֮��  
1��user.msgHander["FixTime"] = function (self,msg)  
- vision.lua����Ұģ�顣  
�����֮��  
1��function block:RemoveObserver(o)  --�ƶ�observerģ�飿  
2��function visionMgr:getBlockByPoint(pos) --��Ұ���ģ�飿  
3��function visionMgr:calUserVisionBlocks(user)  --��Ұ��֪ͨ�û�ģ�飿  
4��function visionMgr:updateViewPort(user) ��  



