### Triggers added to

org.adaptivecellsj.testbed.ejb.TestBean => simulateBusinessLogic
org.adaptivecellsj.testbed.ejb.TargetEJBs => getFirstCallee
org.adaptivecellsj.testbed.ejb.TargetEJBs => getSecondCallee

Ran for each of the configs


####CONFIG 2
```
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@45b02f9
  parameters [config2]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@73202baa
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB3:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@73202baa
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@366c80e4
  parameters [config2]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@d8214a6
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@d8214a6
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
```


####CONFIG 3

```
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@5a236b76
  parameters [config3]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@4b643e35
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB2:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@4b643e35
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@15af036c
  parameters [config3]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@1509b293
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB4:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@1509b293
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@62ec1663
  parameters [config3]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@79b1f051
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB6:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@79b1f051
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@437cbc63
  parameters [config3]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@32342a32
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@32342a32
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
```


####CONFIG 6 
```
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@408add78
  parameters [config6]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@5cd21262
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB2:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@5cd21262
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@c070b06
  parameters [config6]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@2264bd15
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB4:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@2264bd15
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@51a9e7fc
  parameters [config6]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@69bd7b46
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB5:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@69bd7b46
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@e135f2b
  parameters [config6]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@19cd0745
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@19cd0745
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
```

####CONFIG 7
```
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@3579c3a8
  parameters [config7]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@4d1c6605
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB3:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@4d1c6605
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@79636b28
  parameters [config7]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@6e104d5a
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@6e104d5a
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
```


####CONFIG 8
```
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@3658cfe9
  parameters [config8]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@b9e5df
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB2:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@b9e5df
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@7dcb2e90
  parameters [config8]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@265e3075
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB4:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@265e3075
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@3f4e2f38
  parameters [config8]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@5070dd7c
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB5:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@5070dd7c
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value TB6:Stateless
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@73b512a
  parameters [config8]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@464ce20b
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@464ce20b
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  object org.adaptivecellsj.testbed.ejb.TestBean@7e2fcce3
  parameters [config8]

trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@74348bcd
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getFirstCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method enter:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  object org.adaptivecellsj.testbed.ejb.TargetEJBs@74348bcd
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TargetEJBs
  methodName getSecondCalee
  methodSignature ()Lorg/adaptivecellsj/testbed/ejb/TestBeanIF;
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
trigger method exit:
  declaringClass org/adaptivecellsj/testbed/ejb/TestBean
  methodName simulateBusinessLogic
  methodSignature (Ljava/lang/String;)V
  return value null
```