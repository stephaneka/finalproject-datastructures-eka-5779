#include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include<conio.h>

struct game{
 char name;
 int power;
 struct game *parent;
 struct game *left;
 struct game *right;
};
struct game *root=NULL;

void clrscr(){
 system("@cls||clear");
}


void buat_node(struct game *&node, int level, int max_level){
 if(level>max_level) return;
 
 // buat node di sini.
 struct game *new_node=(struct game *)malloc(sizeof(struct game));
  
 if(root==NULL){
  root=new_node;
  root->left=NULL;
  root->right=NULL;
 }
 else{
  if(node->left!=NULL) cek_posisi()
 }
 
 
}

void tree(int count){ // count untuk menyimpan jumlah tim yang bertanding.
 
 int max_level = 1;
 int temp=1;
 for(int i=0; i<100; i++){
  if(temp==count){
   max_level+=i;
   break;
  }
  else{
   temp*=2;
  }
 }
 
 // jumlah node dalam tree = count*2-1
 count = count*2-1;
 
 while(count--){ // berulang sebanyak "count" kali.
  
  // batasi level
  int level = 1;
  
  if(root==NULL){
   
  }
  else{
   
  }
  
 }
}

void add(){
 struct game *ptr, *node;
 struct game *new_node=(struct game *)malloc(sizeof(struct game));
 char name[100];
 int power;
 do{
  printf("Input Name of Grup: ");
  scanf("%[^\n]",name);
 }while(strlen(name)<3||strlen(name)>100);
 do{
  printf("Input Power: ");
  scanf("%d",&power);
 }while(power<1 || power>100);
 
 if(root==NULL){
  root=new_node;
  root->left=NULL;
  root->right=NULL;
  printf("--- Add New Phone Success ---\n");
 }
 else{
  int counter=1;
  ptr=root;

  while(ptr!=NULL){
   node=ptr;
   if(new_node->code<ptr->code){
    ptr=ptr->left;
   }
   else{
    ptr=ptr->right;
   }
   counter++;
  }
 }
}

void view(){
}

void battle(){
 if (child<parent){
  
 }
}
int main(){
 clrscr();
 int pilih;
 do{
  printf("WELCOME TO THE JUNGLE\n");
  printf("=======================\n");
  printf("1. Add New Group\n");
  printf("2. View All Group\n");
  printf("3. Match Battle\n");
  printf("4. Exit\n");
  do{
   printf(">> Input Choice: ");
   scanf("%d",&pilih);
  }while (pilih<1||pilih>4);
  switch(pilih){
   case 1:{
    
    break;
   }
   case 2:{
    break;
   }
   case 3:{
    break;
   }
   case 4:{
    break;
   }
  }
 }while(pilih!=4); 
}
