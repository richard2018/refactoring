
������֯��ĺ���
	Extract Method ����δ���Ž�һ��������������ú������ƽ��͸ú�������;
	Inline Method �ں������õ���뺯�����壬Ȼ���Ƴ��ú���
	Inline Temp �����жԸñ��������ö������滻Ϊ������ֵ���Ǹ����ʽ����
	Replace Temp with Query ��������ʽ������һ������������
	Introduce Explaining Variable ���ø��ӱ��ʽ��������һ���֣��Ľ���Ž�һ����ʱ�������Դ˱������������ͱ��ʽ��;
	Split Temporary Variable ���ÿ�θ�ֵ������һ�������ġ���Ӧ����ʱ����
	Remove Assignments to Parameters ��һ����ʱ����ȡ���ò����ĸ�ֵ���
	Replace Method with Method Object ����������Ž�һ�����������У����һ���ֲ������ͳ��˶����ڵ�ֵ��
		Ȼ����Ϳ�����ͬһ�������н�������ͺ����ֽ�Ϊ����С�ͺ���
	Substitute Algorithm �����������滻Ϊ��һ���㷨

�ڶ���֮���������
	Move Method ��ĳ����У��и�����������פclass֮����һ��class���и��ཻ�������ú��ߣ��򱻺��ߵ���
	Move Filed ��target class����һ��new field���޸�source field�������û��������Ǹ���new field
	Extract Class ����һ����class������ص�ֵ��ͺ����Ӿ�class���Ƶ���class
	Inline Class ��class���������԰��Ƶ���һ��class�У�Ȼ���Ƴ�ԭclass
	Hide Delegate ��server�ˣ�ĳ��class�������ͻ���������к�������������ί�й�ϵdelegation
	Remove Middle Man �ÿͻ�ֱ�ӵ���delegate
	Introduce Forergn Method ��client class�н���һ������������һ��server classʵ����Ϊ��һ����
		����ʹ�õ�server class����Ҫһ�����⺯���������޷��޸����class
	Introduce Local Extension ����һ����class��ʹ��������Щ���⺯����
		�������չƷ��Ϊsource class��subclass�����ࣩ��wrapper���⸲�ࣩ

������֯����
	Self Encapsulate Field Ϊ���ֵ������getter��setter������ֻ����Щ����������ֵ��
	Replace Data Value with Object �������������һ������
	Change Value to Reference ��ʵֵ�����Ϊ���ö���
 	Change Reference to Value �������һ��value object
	Replace Array with Object �Զ����滻���飬���������е�ÿ��Ԫ�أ���һ��ֵ���ʾ֮
	Duplicate Observed Data �������ݿ�����һ��domain object�У�����һ��Observeģʽ��
		���Զ�domain object��GUI object�ڵ��ظ����ݽ���ͬ������
	Change Unidirectional Association to Bidirectional ���һ������ָ�룬��ʹ�޸ĺ����ܹ�ͬʱ������������
	Change Bidirectional Association to Unidirectional ȥ������Ҫ�Ĺ���
	Replace Magic Number with Symbolic Constant �Է��ų���/���泣��ȡ��ħ����
	Encapsulate Field ��������Ϊprivate�����ṩ��Ӧ�ķ��ʺ���
	Encapsulate Collection ������������ظ�Ⱥ����һ��ֻ��ӳ�����������class���ṩadd/removeȺ��Ԫ�صĺ���
	Replace Record with Data Class Ϊ��record��¼����һ�������ݶ���dumb data object
	Replace Type Code with Class ��һ���µ�class�滻����ֵ�ͱ���
	Replace Type Code with Subclasses ������ȡ���ͱ��루immutable type code��
	Replace Type Code with State/Strategy ��State/Strategyȡ���ͱ���
	Replace Subclass with Fields �޸���Щ������ʹ���Ƿ���subclass�е�ĳ����������ֵ��Ȼ������subclass

���������ʽ
	Decompose Conditional ��if��then��else���������зֱ���������������
	Consolidate Conditional Expression ����Щ���Ժϲ�Ϊһ������ʽ�������������ʽ������Ϊһ����������
	Consolidate Duplicate Conditional Fragments ������ظ�������Ƶ�����ʽ֮��
	Remove Control Flag ��break����return���ȡ�����Ʊ��
	Replace Nested Conditional with Guard Clauses ʹ�������ȡ��Ƕ������ʽ
	Replace Condional with Polymorphism �Զ�̬ȡ������ʽ
	Introduce Null Object ��null value��Чֵ �滻Ϊnull object��Ч��
	Introduce Assertion ��assersion��ȷ�������ּ���

�򻯺�������
	Rename Method ������������
	Add Parameter ��Ӳ���
	Remove Parameter �Ƴ�����
	Separate Query from Modifier ����������ͬ�ĺ���������һ�������ѯ����һ�������޸�
	Parameterize Method ������һ�������Բ��������Щ��ͬ��ֵ
	Replace Parameter with Explicit Methods ��Ըò�����ÿһ������ֵ������һ����������
	Preserve Whole Object ��ʹ�ô�����������
	Replace Parameter with Methods �ò���������ȥ�������������ֱ�ӵ���ǰһ������
	Introduce Parameter Object ��һ������ȡ����Щ����
	Remove Setting Method class�е�ĳ��ֵ��Ӧ���ڶ��󴴽�ʱ����ֵ��Ȼ��Ͳ��ٸı�
	Hide Method ��һ������������û�б������κ�class�õ�
	Replace Constructor with Factory Method �Թ�������ȡ�����캯��
	Encapsulate Dowmcast ������ת�Ͷ����Ƶ�������
	Replace Error Code with Exception ���쳣ȡ��������
	Replace Exception with Test �Բ���ȡ���쳣

���������ϵ
	Pull Up Field ֵ������
	Pull Up Method ��������
	Pull Up Constructor Body ���캯����������
	Push Down Method ��������
	Push Down Field ֵ������
	Extract Subclass ��������
	Extract Superclass ��������
	Extract Interface �����ӿ�
	Collapse Hierarchy �۵��̳���ϵ
	Form Template Method ����ģ�庯��
	Replace Inheritance with Delegation ��ί��ȡ���̳�
	Replace Delegation with Inheritance �Լ̳�ȡ��ί��

�����ع�
	Tease Apart Inheritance �����ֽ�̳���ϵ��
		���������̳���ϵ��ͬʱ�е���������
	Convert Procedural Design to Objects �����̻����ת��Ϊ������ƣ�
		�����ݼ�¼��ɶ��󣬽���Ϊ�ֿ���������Ϊ������ض���֮��
	Separate Domain from Presentation ���������ʾ����
		��domain logic���������Ϊ���ǽ���������domain classes
	Extract Hierarchy �����̳���ϵ
		�����̳���ϵ����һ��subclass��ʾһ���������	