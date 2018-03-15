# datastruct
##图
###邻接表实现
typedef char VertexType;//顶点类型
typedef int EdgeType;//权值类型

typedef struct EdgeNode //边表结点
{
  int adjvex;
  EdgeType weight;
  struct EdgeNode *next;
}EdgeNode;

typedef struct VertexNode//顶点表结点
{
  VertexType data;
  EdgeNode *firstedge;
}VertexNode,AdjL
