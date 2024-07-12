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
  'vulkan_headers_revision': 'f41928bd4ac3b0451b68898d8e58a6ed5ee99f2b',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8e1076d9363787b4e754ac17e7ee6ab806458f7c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '145675c7915c5041dac106c9827dc0b21992c091',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'd13c1ee715c4674237aca1c775479e1edde87d3c',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6fa08348be2bb8bec31b3fed831458358b1ce4d2',
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
