//���Ȼ�������һ�£��������Ϊ����ϰ������Ϊ������
                          ��Ϊ�˼ܹ�������Ϊ��ϸ�ڣ�
evaluation:
��������мܹ�����Ľ��飬���Թ�ͬѧϰ
ģ�黯��������ϣ������ռ�ĳ�ͻ�������ǰ��ʱ���ѧϰ�ص㣬����Ҳ�ǽ���ص�
���ܷ����Ҳ���˵�����Ǽ����Ի��Ƿǳ������

������һ���׶ν�����������������ܾ��飬���Ŷ��ڻ��������Ե��ң�����ͦ�򵥵ġ�
focus:
����ĿǰҲֻ����ѧϰ�׶Σ���ӭָ��

focus2:
Everything will flow,technology is only the beginning
//1
$()
$('div')
$('#div1')
$('.box')
$('div.box1.box2......');
$('.pox1.pox2............')
$('#div1 .pox2.pox3.pox4 .box2.box3.box4');
$('div[name=��jason��]');
//�ܽ�֧��id,class,tagname,�Լ����class,tagname��class������ʽ��֧�ֺ��ѡ����
//֧������ѡ����
//2
click
same as jquery

//3
hover
same as jquery

//4
animate(json,fn)


For instance:
animate({'width':'500px,'opacity':70,'top':'30px'},function(){alert('ok');})
//ע��top,left�˶���ǰ���Ǳ�����pos:rea����pos:abs

//5
show
same as jquery
//6
hide
same as jquery
//7
fadeIn
same as jquery
//8
fadeOut
same as jquery
//9
slideUp
same as jquery
//10
slideDown
same as jquery
//11
css
same as jquery
//12
attr
same as jquery
//13
toggle
For instance:
$('#div1').toggle(fn1,fn2,fn3);
//�����������ڵ��div��ʱ������ִ��


///////////////////////dom�ڵ�
//14
eq()
same as jquery

//15
find()
same as jquery

////////
16
index()
same as jquery

//17
bind()
For instance:
$('#div1').bind('click',fn);
//attention: ��Ҫ��hover�����ҷ�ģ�����ϵͳ�Դ���
//18
each
//����dom�ڵ�
For instance:$('div').each(function(index,value){

   $(this).click(function{
     alert(index);
   });
})

//19
$.each()
//��������
For instance:$.each(arr1,function(index,value){

   alert(index);
});

//20
onscroll()
For instance:
$('div').onscroll(function(bStop){
   if(bStop)
    {
     console.log('mouse down');
    }
    else
   {
     console.log('mouse up');
    }
},fn2,fn3.....);
//fn2,fn3ʹ��Ч������һ����ͬ������ĵ�һ����������������¹���

//21
stop()
For instance:
$('#div1').stop();
//���԰����ڽ��еĶ���ֹͣ
//22
$('#div1').text();
//same as jquery
//��֧�ֶ��Ԫ�صĻ�ȡ�����޸�
//23
$('#div1').html();
//same as jquery
//��֧�ֶ��Ԫ�صĻ�ȡ�����޸�
//24
$('#input1').val();
//same as jquery
//��֧�ֶ��Ԫ�صĻ�ȡ�����޸�
//25
$('#div1').append();
//same as jquery
//��֧�ֶ��Ԫ�صĻ�ȡ�����޸�
//26
$('#div1').prepend();
//same as jquery
//��֧�ֶ��Ԫ�صĻ�ȡ�����޸�
//27
$('#div1').remove();
//same as jquery
//��֧�ֶ��Ԫ�صĻ�ȡ�����޸�
//28
$('#div1').empty();
//same as jquery
//��֧�ֶ��Ԫ�صĻ�ȡ�����޸�
//29
$('#div1').width();
//same as jquery
//30
$('#div1').height();
//same as jquery
//31
$('#div1').innerHeight();
//32
$('#div1').innerWidth;
//33
$('#div1').outerWidth;
//34
$('#div1').outerHeight();
//35
$('#div1').parent();
//36
$('#div1').parents();
//37
$('#div1').parentsUntil('body');
//38
$('#div1').children('ss');
//39
$.ajax('get','2.php','x=123&y=456',function(result)
{
    console.log(result);
});
//40
aboslute
$('div').absolute;
���Ը��ķǾ��Զ�λΪ���Զ�λ�������˶�������������
��������
//41
siblings
same as jquery







