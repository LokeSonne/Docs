

SocketInputExtensions Class
===========================





Namespace
    :dn:ns:`Microsoft.AspNetCore.Server.Kestrel.Internal.Http`
Assemblies
    * Microsoft.AspNetCore.Server.Kestrel

----

.. contents::
   :local:



Inheritance Hierarchy
---------------------


* :dn:cls:`System.Object`
* :dn:cls:`Microsoft.AspNetCore.Server.Kestrel.Internal.Http.SocketInputExtensions`








Syntax
------

.. code-block:: csharp

    public class SocketInputExtensions








.. dn:class:: Microsoft.AspNetCore.Server.Kestrel.Internal.Http.SocketInputExtensions
    :hidden:

.. dn:class:: Microsoft.AspNetCore.Server.Kestrel.Internal.Http.SocketInputExtensions

Methods
-------

.. dn:class:: Microsoft.AspNetCore.Server.Kestrel.Internal.Http.SocketInputExtensions
    :noindex:
    :hidden:

    
    .. dn:method:: Microsoft.AspNetCore.Server.Kestrel.Internal.Http.SocketInputExtensions.ReadAsync(Microsoft.AspNetCore.Server.Kestrel.Internal.Http.SocketInput, System.Byte[], System.Int32, System.Int32)
    
        
    
        
        :type input: Microsoft.AspNetCore.Server.Kestrel.Internal.Http.SocketInput
    
        
        :type buffer: System.Byte<System.Byte>[]
    
        
        :type offset: System.Int32
    
        
        :type count: System.Int32
        :rtype: System.Threading.Tasks.ValueTask<System.Threading.Tasks.ValueTask`1>{System.Int32<System.Int32>}
    
        
        .. code-block:: csharp
    
            public static ValueTask<int> ReadAsync(this SocketInput input, byte[] buffer, int offset, int count)
    

