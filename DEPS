# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b937eae5e2ae1e29efe8f8775feaa434239806d2',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '41302b214f02313334f81e12121b793414990917',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'babee77020ff82b571d723ce2c0262e2ec0ee3f1',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '31a9403f7a96336545467fc7949fe4a67678179f',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0aae9c6b5f99d63a5eb7d69a3a1a95e2fa239bc2',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '39a660c6a807ba0be67fdc4a4d6a0bdca24821a6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e8a4ce73f3244d814ccc84e723bb0442fab4dcf7',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9a3f4105c16bde4e2717eeab0fcc5a49236f7294',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '2dfc4cb7ad9ca40ed6fe74c96bdde879b9cdc846',
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
