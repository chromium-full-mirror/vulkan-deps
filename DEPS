# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'ba5c010c590761d0321bd16e915536ef4f9aad8d',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '65c8c768cad2b942b518c42f338696a75138de8f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '3c355ec439dcf821c50fb4660ef0e50d19ae2b63',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9f2ccaef5f70c32bcd6c911a2b09dbb26106b437',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'fc6c06ac529e4b4b6e34c17cc650a8f62dee2eb0',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'f8616928ee19f6c7fd648c1cf1f456cba3771855',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'b47676a03827fc0c287409b243b1fd62886e79c0',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5f26cf65a18bc89a8e3d6569c14314b6fdac8d4d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd9fd55f3a3a4cfd2b1a02f1d6bbd38d18d993326',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
