#include<stdio.h>
#include<string.h>
#include<math.h>
#include<stdlib.h>
#include<time.h>
#define N 100
 


struct student 
{
	char name[20];//学生姓名
	int xh;//学号
	int bh;//班级号
	int rc;//答对次数
	int wc;//答错次数
}stu[N];//定义结构体变量 




char f; 
FILE *fp;//定义指向文件的指针
int choice,sum;//choice判断要进行的程序;sum记录输入错误的次数;
int e;
int i,n;
int a;
int b;
char c;
int xs;//记录学生号数
int zs;//班级总数
int u;
int j,k,max;//order的变量




void luru(struct student stu[N]);//录入
void suijitw(struct student stu[N]);//随机提问
void quedingtw(struct student stu[N]);//直接确定提问
void shuchu(struct student stu[N]);//输出文件
void shuchu(struct student stu[N]);//输出文件
void banhaopx(struct student stu[N]);//班号排序
void xuehaopx(struct student stu[N]);//学号排序
void order(struct student stu[N]);//回答情况排序
void duqu(struct student stu[N]);//读取
void xieru(struct student stu[N]);//写入
int count;//判断学生的数目
struct student t;




int main()
{
	system("color F2");//改变运行框和文字的颜色
	do
	{
		printf("程序初始化中\n输入'1'开始录入新学生信息;输入'2'开始读取文件\n");
		scanf("%d",&e);
	    switch(e)
		{
		case 1:luru(stu);break;
		case 2:duqu(stu);break;
		default:printf("无效的选择!请重新输入!\n");break; 
		}
	}while(e!=1&&e!=2);
	system("cls");//清屏
	do
	{
		printf("----------------------------------------------\n"); 
		printf("\t+    课堂提问管理系统     +\n"); 
		printf("----------------------------------------------\n"); 
		printf("\t  ***************\n"); 
		printf("\t   1、随机提问\n");
		printf("\t   2、直接提问\n");
		printf("\t   3、浏览回答情况\n"); 
		printf("\t   4、回答情况排序\n"); 
		printf("\t   5、退出系统\n");    
  		printf("\t  ***************\n");  
		printf("请输入你的选择\n"); //输出菜单 
		scanf("%d",&choice); //输入选择 
		fflush(stdin);   //清空缓冲区    
		if (choice>5||choice<=0) //防止输入错误而带来错误
  		{ 
   			sum++; 
   			if (sum>=3) 
  			{ 
   				printf("输入错误次数过多,程序将重新开始\n"); 
    			system("pause");        
    			system("cls"); 
  			 } 
  		} 
  		switch (choice)      
  		{ 
  			case 1:
				suijitw(stu);
				break;//进行随机提问  
  			case 2:
				quedingtw(stu);
				break;//进行直接提问
  			case 3:
				xuehaopx(stu);
				break;//浏览学生回答情况 
  			case 4:
				order(stu);
				break; //回答情况排序
			case 5:
				system("cls");
				xieru(stu);
				printf("感谢您使用课堂提问管理系统,正在关掉程序\n");
				system("pause");
				break;
  			default:
				printf("无效的选择!请重新输入!\n");
				break; 
 		 } 
 	}
 	while(choice!=5);
	system("cls");
 	printf("演示结束，谢谢\n");  
 	return 0;
}





void luru(struct student stu[N])//自定义输入函数
{
	system("cls");
	printf("请输入您要录入的学生信息总数:\n");
	scanf("%d",&n);
	for(i=0;i<n;i++)
	{
 	printf("请添加学生的信息\n");
 	printf("请输入学生的姓名\n");
 	scanf("%s",stu[count].name);//输入学生姓名
	printf("请输入学生的学号\n");
 	scanf("%d",&stu[count].xh);//输入学生学号
 	printf("请输入学生的班号\n");
 	scanf("%d",&stu[count].bh);//输入学生班号 
 	printf("请输入学生的答对次数\n");
 	scanf("%d",&stu[count].rc);//输入学生答对次数 
 	printf("请输入学生的答错次数\n");
 	scanf("%d",&stu[count].wc);//输入学生答错次数
    count++;//计算学生人数
	system("cls"); 
	}
}





void quedingtw(struct student stu[N])//直接提问学生
{
	system("cls");
    printf("提问几号同学?\n");
	scanf("%d",&xs);
    printf("该同学答对了吗？");
	for(i=1;i!=0;)
	{
		printf("请输入对r或错w\n");
		c=getchar();
		scanf("%c",&c);
		if(c==114) 
		{
			stu[xs-1].rc++;//该学生答对次数加1
			i=0;
		}
		if(c==119)
		{
			stu[xs-1].wc++;//该学生答错次数加1
			i=0;
		}
		if(c!=114&&c!=119)
		{
			printf("输入错误。请重输入\n");
			i++;
		}
	}
	system("pause");
	system("cls");
}





void suijitw(struct student stu[N])//随机提问学生
{
	system("cls");
    zs=count;
    srand((int)time(NULL));//随机抽取
	xs=rand()%zs+1;
    printf("请%d号同学回答\n",xs);
    printf("该同学答对了吗？");
	for(i=1;i!=0;)
	{
		printf("请输入对r或错w\n");
		c=getchar();
		if(c=='r') 
		{
			stu[xs-1].rc++;//该学生答对次数加1
			i=0;
		}
		else if(c=='w')
		{
			stu[xs-1].wc++;//该学生答错次数加1
			i=0;
		}
		else
		{
			printf("输入错误。请重输入\n");
			i++;
		}
	}
	system("pause");
	system("cls");
}





void duqu(struct student stu[N])//读取历史文件
{  
 	system("cls");
	i=0; 
 	u=1;//历史文件的确定 
 	fflush(stdin);//清空栈 
 	if (u==1) 
 	{ 
  		if((fp=fopen("stu.txt","r"))==NULL) 
  		{  
   			printf("无法打开文件\n");  
   			exit(0); 
  		} 
  		fread(&stu[i],sizeof(struct student),1,fp);  //读取历史文件 
  		count=0; 
  		count++; 
  		i++; 
  		while(fread(&stu[i],sizeof(struct student),1,fp)) 
  		{  
   			i++;  
   			count++; 
  		} 
  		fclose(fp); 
  		printf("历史文件读取完毕!\n"); 
		system("pause");
 	} 
 	else return;
}





void shuchu(struct student stu[N])//输出学生答题情况
{
	 system("cls");//清屏 
	 if(count==0)//判断目前是否有提问学生 
	 {
		printf("当前并未提问学生\n");
 		return;
	 }
 	else
 	{
  		for(i=0;i<count;i++)
  		{
        	printf("姓名:%s\t",stu[i].name);//输出姓名 
        	printf("学号:%d\t",stu[i].xh);//输出学号 
        	printf("班号:%d\t",stu[i].bh);//输出班号 
			printf("答对次数:%d\t",stu[i].rc);//输出答对次数
			printf("答错次数:%d\t",stu[i].wc);//输出答错次数
			printf("\n");
  		}
 	}
	system("pause");
	system("cls");
}




void xieru(struct student stu[N])//保存学生回答情况
{
	i=0;
 	printf("请选择是否要存入数据:'y'还是'n'?\n"); 
 	scanf("%c",&f); //判断是否写入文件 
 	fflush(stdin); 
	while(f!='y'&&f!='n')
 	{ 
  		if (f!='y'&&f!='n') 
   		printf("输入错误,请重新输入\n"); 
  		printf("以下操作将会覆盖已存储的数据,确定请输入'y'或'n'?\n"); 
  		scanf("%c",&f); 
  		fflush(stdin); 
 	} 
 	if (f=='y') 
 	{ 
  		if((fp=fopen("stu.txt","w"))==NULL) 
  		{  
   			printf("无法打开文件\n");  
   			exit(0); 
  		} 
  		for(i=0;i<count;i++)   
  		{
   			fwrite(&stu[i],sizeof(struct student),1,fp); //将学生回答情况写入文件 
  		} 
  		fclose(fp); 
  		if(count==0)//判断是否有内容可以保存  
   			printf("没有文件，无法保存\n"); 
  		else 
   			printf("保存完毕\n"); 
  			system("pause"); 
 	} 
 	else  
  		return;
}


void banhaopx(struct student stu[N])//按班级排序
{
	system("cls");
	for(j=0;j<count;j++)
	{
		max=j;
		for(k=j+1;k<count;k++)    
       	if(stu[k].bh<stu[max].bh)
		{
			t=stu[k];
			stu[k]=stu[max];
			stu[max]=t;
		}
	}
	shuchu(stu);
}


void xuehaopx(struct student stu[N])//按学号排序
{ 
    system("cls"); 
 	for(j=0;j<count;j++) //学号从小到大
	{
		max=j;
		for(k=j+1;k<count;k++)    
       	if (stu[k].xh<stu[max].xh)
		{
			t=stu[k];
			stu[k]=stu[max];
			stu[max]=t;
		}
	}
	shuchu(stu);
}





void order(struct student stu[N])//按回答情况排序
{ 
    system("cls"); 
 	printf("请输入你想要进行排序的方式\n");
 	printf("1、答对次数 2、答错次数\n"); 
 	scanf("%d",&choice); //输入选项
	if(choice>=1&&choice<=2)
	{
		printf("排序完成");
		system("pause");
	    system("cls");
	}
 	switch(choice) 
 	{
 		case 1:
			for(j=0;j<count;j++)    
     		{ 
      			max=j;  
      			for(k=j+1;k<count;k++)    
       				if (stu[k].rc>stu[max].rc)    
       				{
				   		t=stu[k];
				   		stu[k]=stu[max];
				   		stu[max]=t;
					}     
        	};
	shuchu(stu);
			break; //按答对次数从大到小排序
 		case 2:
			for(j=0;j<count;j++)     
     		{ 
      			max=j;  
      			for (k=j+1;k<count;k++)    
       				if (stu[k].wc>stu[max].wc)    
       				{
			   			t=stu[k];
			   			stu[k]=stu[max];
			   			stu[max]=t;
					}   
        	};
	shuchu(stu);
			break; //按答错次数从大到小排序 
 		
 	default:
	 	printf("无效的选择!请重新输入!\n");
		system("pause");
		break; 
    }
	system("cls");
}

