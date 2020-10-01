# ai_pacman

### Câu 1 - 4:
Thực hiện bằng cách kiểm tra xem node đã được thăm chưa. Nếu chưa ta đẩy node đó vào danh sách các node đã thăm và kiểm tra nó có phải trạng thái mục tiêu hay không. 
### Câu 5:
Hoàn thiện các hàm trong class CornersProblem.:
-  init : Lưu lại startingGameState để dùng cho các câu sau.
- getStartState: trả về vị trí bắt đầu và list các corners đã thăm
-  isGoalState: Kiểm tra số corner đã thăm đã bằng số corner của mê cung chưa.
-  getSuccessors  : Xét vị trí hiện tại và list các corner đã thăm, xét vị trí tiếp theo (không phải tường) có phải là corner không và đã được thăm chưa nếu chưa cập nhật list corner đã thăm và list successor.
### Câu 6:
Hoàn thiện hàm cornersHeuristic: Tìm khoảng cách corner xa nhất mà chưa được thăm với vị trí hiện tại sử dụng hàm có sẵn mazeDistance.
### Câu 7:
Hoàn thiện hàm foodHeuristic: Tìm khoảng cách vị trí thức ăn xa nhất với vị trí hiện tại sử dụng hàm có sẵn mazeDistance.
### Câu 8:
Hoàn thiện hàm:
- findPathToClosestDot trong class ClosestDotSearchAgent: Sử dụng bfs, ucs và astar cho kết quả tốt nhất.
- isGoalState trong class AnyFoodSearchProblem: Tìm vị trí của điểm thức ăn cần ăn gần nhất so với vị trí hiện tại, so sánh vị trí đó có trùng với ví trí hiện tại không, nếu trùng đó chính là điểm đích.
