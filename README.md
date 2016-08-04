 SAMPFunktionen:                                                                                                            
      IsSAMPAvailable()                         PrГѓВјft, ob man in den Chat schreiben kann & ob GTA geladen ist            
      isInChat()                                PrГѓВјft, ob der Spieler gerade chattet oder in einem Dialog ist            
      getUsername()                             Liest den Namen des Spielers aus                                            
      getId()                                   Liest die Id des Spielers aus                                               
      SendChat(wText)                           Sendet eine Nachricht od. einen Befehl direkt an den Server                 
      addChatMessage(wText)                     FГѓВјgt eine Zeile in den Chat ein (nur fГѓВјr den Spieler sichtbar)        
      showGameText(wText, dwTime, dwTextsize)   Zeigt einen Text inmitten des Bildschirmes an  					            
      playAudioStream(wUrl)                     Spielt einen "Audio Stream" ab                                              
      stopAudioStream()                         Stoppt den aktuellen Audio Stream                                           
	  GetChatLine(Line, Output)		            Liest die eingestellte Zeile aus,				                            
					                            Optionale Parameter (timestamp=0, color=0)			                        
	  blockChatInput() 							Eine Funktion um Messages zum Server zu blockieren			                
   	  unBlockChatInput() 						Eine Funktion um Messages zum Server zu entblockieren			            												                                                                    
      getServerName()                           Ermittelt den ServerNamen (HostName)  										
      getServerIP()                             Ermittelt die IP des Servers  										        
      getServerPort()                           Ermittelt den Port des Servers  										    
      CountOnlinePlayers()                      Ermittelt wie viele Spieler auf dem Server Online sind.                     		                                                                    
	  getWeatherID()			                Ermittelt ob der Spieler freezed ist                                        
	  getWeatherName()			                Ermittelt ob der Spieler freezed ist                                        											                                                                    
      patchRadio() (interner stuff) 										                                                
      unPatchRadio() (interner stuff)											                                            													                                                                   
 SAMP Dialog Funktionen (v0.3.7):																	                        
	 isDialogOpen()  PrГјft, ob gerade ein Dialog angezeigt wird (gibt true oder false zurГјck)	                       		
	 getDialogStyle()  Liest den Typ des (zuletzt) angezeigten Dialogs aus (05)                      						
	 getDialogID()  Liest die ID des (zuletzt) angezeigten Dialogs aus (auch vom Server)	                        			
	 setDialogID(id)  Setzt die ID des (zuletzt) angezeigten Dialogs auf [id]				                        			
	 getDialogIndex()  Liest die (zuletzt) ausgewГ¤hlte Zeile des Dialogs aus 				                        		
	 getDialogCaption()  Liest die Гњberschrift des (zuletzt) angezeigten Dialogs aus 			                       		
	 getDialogText()  Liest den Text des (zuletzt) angezeigten Dialogs aus (auch bei Listen)                              	
	 getDialogLineCount()  Liest die Anzahl der Zeilen/Items des (zuletzt) angezeigten Dialogs aus                        	
	 getDialogLine(index)  Liest die Zeile an der Stelle [index] mittels getDialogText aus 		                        	
	 getDialogLines()  Liest die Zeilen mittels getDialogText aus (gibt ein Array zurГјck)			                      	
	 isDialogButton1Selected()  PrГјft, ob Button1 des Dialogs ausgewГ¤hlt ist 						                       	
     getDialogStructPtr()  Liest den Base Pointer zur Dialogstruktur aus (intern genutzt)			                        																										                        	
	 showDialog(style, caption, text, button1, button2, id)  Zeigt einen Dialog an (nur lokal)	                        												                                                                    
 ExtraPlayerFunktionen:                                                                                                    
	  getTargetPed(dwPED)   			        Zeigt die PEDID, des Spielers, auf den man zielt.                          
      getPedById(dwId)                          Zeigt die PEDId zu der Id.                                                 
      getIdByPed(dwId)                          Zeigt die Id der PEDId.                                                    
      getStreamedInPlayersInfo()                Zeigt Informationen ГѓВјber die gestreamten Spieler.                        
      callFuncForAllStreamedInPlayers()         FГѓВјhrt bestimmte Funktionen, fГѓВјr die gestreamten Spieler aus.          
	  getDist(pos1,pos2)   			            Rechnet den Abstand zwischen zwei Positionen aus.                           
      getClosestPlayerPed()                     Zeigt die PEDID, des Spielers, der am nahesten zu einem steht.             
      getClosestPlayerId()                      Zeigt die Id, des Spielers, der am nahesten zu einem steht.                 
	  getPedCoordinates(dwPED)   			    Zeigt die Koordinaten, der PEDID.                                          
      getTargetPosById(dwId)                    Zeigt die Position, zu der angegebenen Id.                                  
      getTargetPlayerSkinIdByPed(dwPED)         Zeigt den Skin, zu der angegebenen PEDID.                                  
      getTargetPlayerSkinIdById(dwId)           Zeigt den Skin, zu der angegebenen ID.                                      
      calcScreenCoors(fX,fY,fZ)                 > WordToScreen Funktion <                                                   
 														                                                                    
 ExtraPlayerFahrzeugFunktionen:                                                                                           
     getVehiclePointerByPed(dwPED)   	    	Zeigt die PEDID des Autos.                                                 
	 getVehiclePointerById(dwId)   			   Zeigt die PEDID des Autos.                                                 
     isTargetInAnyVehicleByPed(dwPED)          Zeigt ob der Spieler in einem Auto ist.                                     
     isTargetInAnyVehicleById(dwId)            Zeigt ob der Spieler in einem Auto ist.                                     
     getTargetVehicleHealthByPed(dwPED)        Zeigt ob der Spieler in einem Auto ist.                                     
     getTargetVehicleHealthById(dwId)          Zeigt ob der Spieler in einem Auto ist.                                     
     getTargetVehicleTypeByPed(dwPED)          Ermittelt den FahrzeugTyp (Auto, LKW etc.)                                  
     getTargetVehicleTypeById(dwId)            Ermittelt den FahrzeugTyp (Auto, LKW etc.)                                  
     getTargetVehicleModelIdByPed(dwPED)       Ermittelt die Fahrzeugmodell ID                                             
     getTargetVehicleModelIdById(dwId)         Ermittelt die Fahrzeugmodell ID                                             
     getTargetVehicleModelNameByPed(dwPED)     Ermittelt den Fahrzeugmodell Namen 				                            
     getTargetVehicleModelNameById(dwId)       Ermittelt den Fahrzeugmodell Namen 				                            
     getTargetVehicleLightStateByPed(dwPED)    Ermittelt den Lichtzustand des Autos 			                            
     getTargetVehicleLightStateById(dwId)      Ermittelt den Lichtzustand des Autos 			                            
     getTargetVehicleEngineStateByPed(dwPED)   Ermittelt den Motorzustand des Autos 			                            
     getTargetVehicleEngineStateById(dwId)     Ermittelt den Motorzustand des Autos 			                            
     getTargetVehicleLockStateByPed(dwPED)     Ermittelt ob das Auto auf oder zu ist 			                            
     getTargetVehicleLockStateById(dwId)       Ermittelt ob das Auto auf oder zu ist 			                            
     getTargetVehicleColor1ByPed(dwPED)        Ermittelt die 1. ColorID des Autos 			                            
     getTargetVehicleColor1ById(dwId)          Ermittelt die 1. ColorID des Autos 			                            
     getTargetVehicleColor2ByPed(dwPED)        Ermittelt die 2. ColorID des Autos 			                            
     getTargetVehicleColor2ById(dwId)          Ermittelt die 2. ColorID des Autos 			                            
     getTargetVehicleSpeedByPed(dwPED)         Ermittelt die Geschwindigkeit des Autos			                            
     getTargetVehicleSpeedById(dwId)           Ermittelt die Geschwindigkeit des Autos			                            												                                                                    
 ScoreboardFunktionen:                                                                                                      
     getPlayerScoreById(dwId)                  Zeigt den Score zu der Id                                                   
     getPlayerPingById(dwId)                   Zeigt den Ping zu der Id                                                    
     getPlayerNameById(dwId)                   Zeigt den Namen zu der Id                                                   
     getPlayerIdByName(wName)                  Zeigt die Id zu dem Namen                                                   
     updateScoreboardDataEx()                  Aktualisiert Scoreboard Inhalte (wird implizit aufgerufen)                  
     updateOScoreboardData()                   Aktualisiert Scoreboard Inhalte (wird implizit aufgerufen)                  
	 isNPCById(dwId)   			            Zeigt an ob die ID ein NPC 						                            													                                                                    
 Spielerfunktionen:                                                                                                          
     getPlayerHealth()                          Ermittelt die HP des Spielers                                               
     getPlayerArmour()                          Ermittelt den RГѓВјstungswert des Spielers                                  
 	 getPlayerInteriorId()			            Ermittelt die Interior ID wo der Spieler ist 		                        
 	 getPlayerSkinId()			                Ermittelt die Skin ID des Spielers           		                        
 	 getPlayerMoney() 			                Ermittelt den Kontostand des Spielers (nur GTA Intern)                      
	 getPlayerWanteds()			                Ermittelt die Wantedanzahl des Spielers (nur bis 6 Wanteds)                 
	 getPlayerWeaponId()			            Ermittelt die Waffen ID des Spielers                                        
	 getPlayerWeaponName()			            Ermittelt den Namen, der Waffe des Spielers                                 
	 getPlayerState()			                Ermittelt den "Status" des Spielers (Zu FuГѓЕё, Fahrer, Tot)                
	 getPlayerMapPosX()			                Ermittelt die XPosition auf der Map im Menu                                
	 getPlayerMapPosY()			                Ermittelt die YPosition auf der Map im Menu                                
	 getPlayerMapZoom()			                Ermittelt den Zoom auf der Map im Menu                                      
	 IsPlayerFreezed()			                Ermittelt ob der Spieler freezed ist                                                                           
 Fahrzeugfunktionen:                                                                                                         
     isPlayerInAnyVehicle()                    Ermittelt, ob sich der Spieler in einem Fahrzeug befindet                   
     getVehicleHealth()                        Ermittelt die HP des Fahrzeugs, in dem der Spieler sitzt                    
 	 isPlayerDriver() 			                Ermittelt ob der Spieler Fahrer des Auto's ist		                        
 	 getVehicleType() 			                Ermittelt den FahrzeugTyp (Auto, LKW etc.)                                  
 	 getVehicleModelId()			            Ermittelt die Fahrzeugmodell ID 				                            
 	 getVehicleModelName() 		            Ermittelt den Fahrzeugmodell Namen 				                            
 	 getVehicleLightState() 		            Ermittelt den Lichtzustand des Autos 			                            
 	 getVehicleEngineState() 		            Ermittelt den Motorzustand des Autos 			                            
 	 getVehicleLockState() 		            Ermittelt ob das Auto auf oder zu ist 			                            
 	 getVehicleColor1() 		                Ermittelt die 1. Farb ID des Autos   			                            
 	 getVehicleColor2() 		                Ermittelt die 2. Farb ID des Autos   			                            
 	 getVehicleSpeed() 		                Ermittelt die Geschwindigkeit des Autos   			                        
 	 getPlayerRadiostationID() 		        Ermittelt die RadiostationID des Autos   			                        
 	 getPlayerRadiostationName() 		        Ermittelt den RadiostationNamen des Autos   			                    
 														                                                                    

 														                                                                    
 Standpunktbestimmung:                                                                                                       
      getCoordinates()                          Ermittelt die aktuelle Position (Koordinaten)                               
	     getPlayerPos(X,Y,Z) 			            siehe oben drГѓВјber 						                                
 														                                                                    

 														                                                                    
      initZonesAndCities()                      Initialisiert eine Liste aller Standartgebiete                              
												(Voraussetzung fГѓВјr die folgenden Funktionen dieser Kategorie)            
      calculateZone(X, Y, Z)                    Bestimmt die Zone (= Stadtteil) aus den geg. Koordinaten                    
      calculateCity(X, Y, Z)                    Bestimmt die Stadt aus den geg. Koordinaten                                 
      getCurrentZonecode()                      Ermittelt die aktulle Zone in Kurzform                                      
      AddZone(Name, X1, Y1, Z1, X2, Y2, Z2)     FГѓВјgt eine Zone zum Index hinzu                                           
      AddCity(Name, X1, Y1, Z1, X2, Y2, Z2)     FГѓВјgt eine Stadt zum Index hinzu                                          
	  IsPlayerInRangeOfPoint(X, Y, Z, Radius)   Bestimmt ob der Spieler in der NГѓВ¤he der Koordinaten ist                  
	  IsIsPlayerInRangeOfPoint2D(X, Y, Radius)  Bestimmt ob der Spieler in der NГѓВ¤he der Koordinaten ist                  
	  getPlayerZone()                   				                                                                    
	  getPlayerCity()                   					                                                                
 Sonstiges:                                                                                                                  
      checkHandles()                                                                                                        
      AntiCrash()								Hilft gegen das abstГѓВјrzen bei Warningscodes                              
 Speicherfunktionen (intern genutzt):                                                                                        
 Memory Functions:                                                                                                           
      checkHandles()                                                                                                        
      refreshGTA()                                                                                                          
      refreshSAMP()                                                                                                         
      refreshMemory()                                                                                                       
      getPID(szWindow)                                                                                                      
      openProcess(dwPID, dwRights)                                                                                          
      closeProcess(hProcess)                                                                                                
      getModuleBaseAddress(sModule, dwPID)                                                                                  
      readString(hProcess, dwAddress, dwLen)                                                                                
      readFloat(hProcess, dwAddress)                                                                                        
      readDWORD(hProcess, dwAddress)                                                                                        
      readMem(hProcess, dwAddress, dwLen=4, type="UInt")                                                                    
      writeString(hProcess, dwAddress, wString)                                                                             
      writeRaw(hProcess, dwAddress, data, dwLen)                                                                            
      Memory_ReadByte(process_handle, address)                                                                              
      callWithParams(hProcess, dwFunc, aParams, bCleanupStack = true)                                                       
      virtualAllocEx(hProcess, dwSize, flAllocationType, flProtect)                                                         
      virtualFreeEx(hProcess, lpAddress, dwSize, dwFreeType)                                                                
      createRemoteThread(hProcess, lpThreadAttributes, dwStackSize, lpStartAddress, lpParameter,                            
      dwCreationFlags, lpThreadId)                                                                                          
      waitForSingleObject(hThread, dwMilliseconds)                                                                          
      __ansiToUnicode(sString, nLen = 0)                                                                                    
      __unicodeToAnsi(wString, nLen = 0)                                                                                    
 by {CM}MurKotik                                                                                                                                                                                                               
      setCoordinates(x, y, z, Interior)          Телепорт персонажа                                                        
      getIP()                                    Выдаёт IP Адрес сервера                                                   
      setIP(IP)                                  Меняет IP Адрес Сервера       (Не доработан)                              
      getHostname()                              Выдаёт Имя сервера                                                        
      setUsername(Username)                      Установить новый Ник          (Не доработан)                              
      colorhud(Цвет)                             Менякет зелёный цвет в игре на указаный                                   
	  setTime(hour)	                             Устанавливает время на сервере                                            
	  getSkinID()   	                         Выдаёт ID Скина вашего персоажа                                           
	  getDialogTitle() 	                         Выдаёт Заголовок последнего диалога                                       
	  getPlayerColor(id)                         Выдаёт ID Цвета ника игрока по ID                                         
	  setPlayerColor(id,color)                   Устанавливает цвет ника игроку по его ID                                  
	  colorToStr(color)	                         Конвертация цвета из десятичной в шестнадцатиричную                       
	  getWeaponId() 	                         Выдаёт ID оружия вашего персонаха                                         
      restartGameEx()                            Рестарт игры (Не отключает от сервера)                                    
      setrestart()                               Установить рестартинг (применить)                                         
      disconnectEx()                             Отключение от сервера                                                     
      WriteProcessMemory(title,addresse,wert,size)  Работас пресетам                                                       
      setCoordinates(x, y, z, Interior)          Телепортирует на указаные кординаты                                       
      writeFloat(hProcess, dwAddress, wFloat)    Работа с памятью процесса                                                 
      writeByte(hProcess, dwAddress, wInt)       Работа с памятью процесса                                                 
      FloatToHex(value)                          Перевот из Float в Hex                                                    
      IntToHex(int)                              Выдаёт интерьер персонажа                                                 
      addChatMessageEx(Color, wText)             Фэйк сообщение с покраской timstamp                                       
      newchat()                                  Обновление чата (пока что отправлением пустых строк)                      
      connect(IP)                                Подключение к серверу по его IP (Пока что без смены Порта)                
      HexToDec(str)                              Перевод из Hex в Dec (Строковых значений)                                 
      getVehicleLockStaterus()                   Перевод из логического значения в "Отткрыто / Закрыто"                    
      getVehicleEngineStaterus()                 Перевод из логического значения в "Заведён / Выключен"                    
      getVehicleLightStaterus()                  Перевод из логического значения в "Выключен / Включён"                    
      getVehicleHealthrus()                      Корекция логического вырожения (Заменяем 1 на пустую переменную)         
by McFree_                                                                                                                
     getPlayerPosById(dwId)                      Вычисляет позицию персонажа                                               
     HexToDecOne(Hex)                            Перевод из Hex в Dec                                                      

by Godarck                                                                                                                  
      GetInterior()                              True or False. Находится ли персонаж в интерьере или нет.                 
      getVehicleSirenState()                     True or False. Включена ли сирена в полицейской машине или нет.           
      CoordsFromRedmarker()                      Считывает координаты метки с карты.                                       

By Unknown                                                                                                                  
      disableCheckpoint()                        Отключает маркер на карте. Disabled REd Marker on map                     
      setCheckpoint(xpos,ypos,zpos,Radius)       Устанавливает маркер на карте. Рекомендуемое значение радиуса             
