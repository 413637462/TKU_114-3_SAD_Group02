# 0714 使用者故事、驗收條件與實作修正

## 小組與專案
- 課程名稱：系統分析與設計
- 日期：115/07/14
- 小組名稱：Group2
- 專案名稱：智慧課程分組與跨系組隊媒合系統
- 7/13 成果資料夾：[0713_Requirements_Code_Agent](../0713_Requirements_Code_Agent)

## 今日完成內容
- 建立 8 則使用者故事與 8 筆功能性需求
- 整理 5 筆非功能性需求、3 筆業務規則、3 筆資料需求與 3 筆限制條件
- 撰寫 10 筆驗收條件與 3 筆需求品質問題
- 排定 MoSCoW 與價值投入優先順序
- 更新實作待辦、程式碼代理任務書與需求-畫面對照表
- 完成第二個可操作切片，支援學生偏好輸入、隊伍申請與任務看板更新

## 本次選擇
- 本次選擇建立第二個可操作切片，延續第一個切片的學生與組長流程。
- 主要操作流程：學生填寫技能與偏好、查看隊伍缺口、提交加入申請、組長新增任務並更新狀態。

## 如何開啟與操作
1. 開啟 [revised_or_second_working_slice/index.html](revised_or_second_working_slice/index.html)
2. 在學生區塊輸入技能與偏好，並點擊「儲存偏好」
3. 點擊隊伍卡片上的「申請加入」
4. 在組長區塊新增任務，並切換任務狀態

## 已通過與未通過的驗收條件
- 已通過：AC-01-01、AC-02-01、AC-03-01、AC-04-01、AC-05-01、AC-NFR-01-01
- 未通過：目前未新增正式登入與正式資料庫，因此不支援正式權限與實際資料持久化

## 已知限制
- 目前為靜態原型，資料會在瀏覽器中暫存
- 不包含正式登入、即時聊天與正式校務系統整合
- 申請與任務狀態為假資料模擬，不作真正的後端保存

## 文件連結
- [使用者故事](user_stories.md)
- [功能性需求](functional_requirements.md)
- [非功能性需求](non_functional_requirements.md)
- [業務規則與資料需求](business_rules_data_constraints.md)
- [驗收條件](acceptance_criteria.md)
- [需求品質檢查](requirements_quality_review.md)
- [需求優先順序](requirements_priority.md)
- [需求文件包初稿](requirements_package_draft.md)
- [需求追溯矩陣](traceability_matrix_draft.md)
- [實作待辦清單](implementation_backlog.md)
- [更新後的程式碼代理任務書](updated_code_agent_brief.md)
- [需求與畫面對照表](requirements_to_screen.md)
- [手動驗收測試](manual_acceptance_test.md)
- [生成式 AI 使用紀錄](ai_code_agent_log.md)

## 本次提交紀錄
- docs: 完成使用者故事與需求文件包初稿
- feat: 完成第二個可操作切片
- test: 補上手動驗收測試與修正紀錄

## 版本紀錄
- 0.1：建立需求文件包初稿
- 0.2：完成第二個可操作切片與手動驗收測試
