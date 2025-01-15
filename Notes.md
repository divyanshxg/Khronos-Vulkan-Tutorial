- Vulkan objects are created or assigned using vkCreateXXX or vkAllocateXXX and then when no longer needed they are destroyed using vkDestroyXXX vkFreeXXX

- there is one parameter they all share, pAllocator . its used to specify callbacks for a custom memory allocator but nullptr is used in this tutorial
