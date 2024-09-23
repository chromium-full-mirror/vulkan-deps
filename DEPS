# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '96899e0f47045846b3b77cd9a9710c6366d9f859',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a24a94aa0d1fc4e5556bdf9c6b2afe8eacc55326',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '2a9b6f951c7d6b04b6c21fe1bf3f475b68b84801',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '24849751c4d16d52994c097d821fdba6f385f2d1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c6391a7b8cd57e79ce6b6c832c8e3043c4d9967b',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fa5cc0539dd634968afa1fb72088b195ecf5e95c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '4c63e845962ff3b197855f3ae4907a47d0863f5a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '6fb0c125afec7b9d724d598f4dca6c61648be35f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6386c9e19f148a43bc7d9130882538329d7bff74',
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
