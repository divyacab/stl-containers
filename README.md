# stl-containers
it is a collection of object in differnt kind
#include<iostream.h>
#include<list>
#include<numeric>
void print(list <double>list)
{
list<double>::iterator key;
for(key=lst begin();key!=lst end();++key)
cout<<*key<<'\t';
cout<<endl;
}
void main()
{
double array[4]={1,2,3,4};
list<double>obj;
for(int i=0;i<4;++i)
obj.push_front(array[i]);
print(obj);
obj.sort();
cout<<"the sorted list is"<<endl;
print(obj);
cout<<"sum is "<<accumulated(obj.begin(),obj.end(1,0.0);
