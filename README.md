12球中，有一个球跟别人的质量不一样，有一个天秤，如何称三次找出这个跟别的球质量不一样的球？

先将球分为3组记为A，B，C，每组四个球，然后称A和B：
称重A和B
If A=B
	If A1A2A3 = C1C2C3，则为C4
		If A4<C4，则C4偏重
		If A4>C4，则C4偏轻
	If A1A2A3 > C1C2C3，则在C1C2C3中，且非正常球偏轻
		If C1 = C2，则为C3，且偏轻
		If C1 > C2，则为C2，且偏轻
		If C1 < C2，则为C1，且偏轻
	If A1A2A3 < C1C2C3，则在C1C2C3中，且非正常球偏重
		If C1 = C2，则为C3，且偏重
		If C1 > C2，则为C1，且偏重
		If C1 < C2，则为C2，且偏重

if A>B
	if A1A2A3B1 = C1C2C3A4，则在B2B3B4中,且非正常球偏轻
	if A1A2A3B1 > C1C2C3A4，则在A1A2A3中,且非正常球偏重
	if A1A2A3B1 < C1C2C3A4，则在A4B1中
		if A4 = C1，则为B1,且偏轻
		if A4 > C1，则为A4,且偏重
		if A4 < C1，则为A4,且偏轻(矛盾)
	
if A<B	
	if A1A2A3B1 = C1C2C3A4，则在B2B3B4中,且非正常球偏重
	if A1A2A3B1 > C1C2C3A4，则在A4B1中
		if A4 = C1，则为B1,且偏重
		if A4 > C1，则为A4,且偏重(矛盾)
		if A4 < C1，则为A4,且偏轻
	if A1A2A3B1 < C1C2C3A4，则在A1A2A3中,且非正常球偏轻	
