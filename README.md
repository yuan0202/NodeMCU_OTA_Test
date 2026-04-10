# NodeMCU_OTA_Test
系統架構概覽 (System Overview) OTA (Over-the-Air) 更新是一種遠端更換設備韌體（Firmware）的技術。在 NodeMCU 的場景下，這通常由 HTTP Client 模式 實現：設備主動向伺服器發起請求，下載新的二進制檔案（.bin），並在不連接 USB 的情況下自我更新。
