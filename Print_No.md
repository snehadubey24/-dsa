<h1> Print no. in reverse order </h1>#include < iostream >  <br/>
using namespace std;    <br/> <br/>

void reverse(int n)  <br/>{
     <br/>if (n<=0) <br/>
    {  <br/>return ; <br/>}
    cout<< n <<" ";<br/>
    reverse(n-1);<br/>
}<br/><br/>


int main() {<br/>
	int n;<br/>
	cin>>n;<br/>
	reverse(n);<br/>
	return 0;<br/>
}
